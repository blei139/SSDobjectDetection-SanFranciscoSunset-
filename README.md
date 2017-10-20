# SSDobjectDetection-SanFranciscoSunset-
This repository is a SSD object detection project, using the dash camera videoes taken from streets of the Sunset District in 
San Francisco.  The object detection algorithm is SSD.  The SSD model is 'ssd_mobilnet_v1_coco'.  The object detection graph is 
'frozen_inference_graph.pb', which has weights baked into the graph as constants and used by tensorflow for object detection.
The ipython script, is SSDobjectDetectionVideoProc.ipynb.  This script detects objects such stop signs, persons, cars, trucks, and traffic
lights.  This script processes each frame in the input video by detecting objects, using openCV to detect traffic light color 
specifically for traffic lights.  Then, it passes the processed image in each frame into a stream output video with SSD object detection 
and openCV traffic light color detection.

Instruction on how to run the ipython script:
1) Open the Anaconda prompt
2) Type "jupyter notebook" will open up an internet browser
3) From your internet browser, click on icons up to the directory where the "SSDobjectDetectionVideoProc.ipynb" ipython script is located.
4) Double click on this file to run the SSD objection detection and openCV traffic light color classification.
5) Once this file is opened up in your browser, double click on the run button will produce the output videoes where the output videos
   are located in the test_videos directory.

Tutorial in the object_detection directory:
1) Read the README file in the object_detection directory
2) Run the object_detection_tutorial.ipynb script in jupyter notebook in Anaconda for more understanding of SSD detection.

My youtube link:
https://youtu.be/L5ejQEwkl1Y
