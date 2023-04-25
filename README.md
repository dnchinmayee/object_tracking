# object_tracking

# Have used Yolov7 to track the object. Files are
  1. detect.py
      # for detection only
          !python detect.py --weights yolov7.pt --source /content/drive/MyDrive/AIassignment/yolov7-object-tracking/inference/images/ai-assignment.mp4
  2. detect_and_track.py
        !python detect_and_track.py --weights yolov7.pt --source /content/drive/MyDrive/AIassignment/yolov7-object-tracking/inference/images/ai-assignment.mp4 --colored-trk
        
        !python detect_and_track.py --weights yolov7.pt --source /content/drive/MyDrive/AIassignment/yolov7-object-tracking/inference/images/ai-assignment.mp4 --save-txt --save-bbox-dim
 
 # weight file is yolo.pt
 Have reduced the mp4 video size to 70MB due to size and to run in GPU. The output result link is
 
 https://drive.google.com/drive/folders/16KlpR14bKETMfp7SXuRR5iliPcGwoiR4?usp=sharing
