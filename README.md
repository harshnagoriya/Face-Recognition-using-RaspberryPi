# Face Recognition Using Raspberry-Pi
Face Recognition System using Raspberry Pi for Marking attendance.

Dependencies
----------------------
- CMAKE
- face_recognition
- numpy
- os
- pymysql
- sys
- imutils
- Amazon Relational Database

Working Mechanism (Architecture)
--------------------

1. Raspberry Pi
2. Android App
3. AWS EC2 Instances

Working prod
-----
- This framework recognizes faces stored in database by creating an xml format of each individual and after recognizing individual, it sends a flag to AWS server to mark the attendence.
- In case of unknown person, it simply updates status *Unknown*.

**Note: Live internet is required for Raspberry Pi to manage this system.**
