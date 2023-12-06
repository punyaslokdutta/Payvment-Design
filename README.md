# Payvment-Design
Payvment provides smart parking solutions.


## Non Funtional Requirements 

1. Real-timeness?
2. Low latency (How much latency is acceptable?)
3. Scaling & High Throughput( 100 parking places * 1000)
(10^5/10^5 = 1 QPS) which is low

## Functional Requirements

1. LP Detection (Bounding box)
2. Acurracy -> [[position, "ABC", confidence]]
3. accessible by api v1/vehicle/{license_plate_no}


## ML Models
1. Object Detection -> Yolo V8 Pretrained(Car, Bike , Truck)
2. License Plate detection (Bounding Box)
3. OCR (Easy OCR)

Datasets 
1. 


## Context/Decision Making: 
1. Training specific to a number plates region (will lead to higher confidence)
2. Processing on Server vs Edge computing for realtimeness

Edge cases: 
