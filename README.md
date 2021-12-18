# HouseNumbersDetection
This is a Tianchi competition, task is to detect house numbers from the given pictures. link: https://tianchi.aliyun.com/competition/entrance/531795/information 
I implemented two different ways, baseline leverages image classification and improved version (which achived 77+% accuracy) leverages Yolo4 (implemented by Alexey team). 
Baseline: it is a multi output classification problem with 11 classes in total, 0 - 9 for possible house number in each digit and 10 for empty.
