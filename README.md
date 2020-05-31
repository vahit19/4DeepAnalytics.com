# The CoronaLytics Project with Live Dashboard and HeatMap
Towards IoT to Artificial Intelligence of Things (AIoT) 

Artificial intelligence (AI) using Deep Learning Technology For Identifying a Person of Interest (POI) in Real World Analytics of COVID-19 Rules For Wearing Face Masks and Social Distances,

Note: CoronaLytics will be custom trained for specific Analytics use-cases in real world, also implementation for Integrating CoronaLytics with Node-Red for AIoT use-cases

As social distancing and face masks become an important tool to combat COVID-19, Government regulations or organizations may wish to be notified when individuals are not wearing a mask and those who do not comply with social distance rules, below is a demo of Istanbul Covid-19 Social Distancing Analysis based on AI Deep Learning based Video Analytics with Live Dashboard,

the demo project streaming video from Cities Public Live Cameras:

[![Covid-19 Istanbul](https://yt-embed.herokuapp.com/embed?v=3P4LBxkxPBA)](https://www.youtube.com/watch?v=3P4LBxkxPBA "Covid-19 Istanbul")


Also CoronaLytics with Live Dashboard and HeatMap, Please kindly see the demo video at this Link:


[![The CoronaLytics](https://yt-embed.herokuapp.com/embed?v=25rIhR1a1sA&feature=youtu.be)](https://www.youtube.com/watch?v=25rIhR1a1sA&feature=youtu.be "The CoronaLytics")

If organizations want to upgrade in-company IP camera infrastructure for this purpose, 4DA offers added value AI solutions to be integrated to their existing security camera systems by custom training of AI models based on data to be collected from the camera viewpoints in their organizations, also these possible to deploy AI models on embedded devices with AIoT solutions.

For all the unknowns surrounding the COVID-19 pandemic, one thing is certain: Containing and rolling back the disease is only possible with reliable information about the prevalence of the infection and its spread. The greatest difficulty now is identifying individuals carrying the virus and all the people who interacted with them.

Proposed technologies can help surveil and monitor diseases and their transmission, but that infrastructure is not yet in place. The new corona-virus outbreak is forcing a reassessment of plans to develop those capabilities and making plain the problems that they will face.

Video analytics technologies are able to detect anomalous behavior in AI powered smart cities, hospitals or any other organizations, also have the potential to notify nurses if a patient’s dressings have not been changed or if a bed-bound patient needs assistance. Video analytics can alert hospital staff if a patient falls by distinguishing between the movement of a person lying down on a bed or sitting on the floor.

As well as helping medical staff improve patient care, video analytics can also increase efficiency. By analyzing patient behavior patterns at different hospital locations and times of the day, analytics can improve staffing levels by providing accurate information about where staff members are being posted, versus where the highest amount of activity is occurring. This can help hospital administrators make the best use of resources and help improve emergency procedures.

The application has a streaming video support from Istanbul City Public Live Cameras as follows:

$ python CoronaLytics_POI_Istanbul.py

What type of camera do you want to use?

 (1) Tourist Camera
 
 (2) City and Traffic Cameras
 
 
Select the Camera you want to process


(0) Anadolu Hisarı

(1) Bağdat Caddesi

(2) Bağdat Caddesi 2

(3) Beyazit Kulesi

(4) Beyazit Meydan

(5) Büyük Çamlıca

(6) Dragos

(7) Emirgan

(8) Galata Kulesi

(9) Hidiv Kasrı 1

(10) Hidiv Kasrı 2

(11) Kadıköy

(12) Karaköy

(13) Kapalı Çarşı

(14) Kız Kulesi

(15) Küçük Çamlıca

(16) Metrohan

(17) Mısır Çarşısı

(18) Miniatürk

(19) Pierre Loti

(20) Salacak

(21) Saraçhane

(22) Sepetçiler Kasrı

(23) Sultanahmet

(24) Taksim

(25) Ulus Parkı

(26) İstiklal Caddesi 1

(27) İstiklal Caddesi 2

The application detects people who are close by and not adhering to the distancing norms and marks them in RED bounding boxes, signifying risk. Others, are in GREEN. The Dashboard at the right, gives a visual representation of the data. The number next to the GREEN and RED icons are the number of SAFE and RISK people. Whereas, the BLACK is the total number of people in the frame. The Pie Chart at the top just plots the SAFE vs AT RISK persons in the frame.


To Do:

For AI on IoT:

- speed up Python as a C++ with effective coding for increasing performances such as CPU and memory profiling, use Cython for compiling, vectorizing variables, manage garbage collection, use multiprocessing + Plus packing projects and freezes (packages) Python applications into stand-alone executables under Windows, GNU/Linux, Mac OS X), Anaconda Packages, 

- Working on speed up AI Apps using compilation and Multiprocessing, we can disable the Global Interpreter Lock (GIL) of Python, then coding such as C++ and Fortran using Cython and Pythran for gaining performances equal to C, by this way we will have machine level coding with variable types annotation like C and at the same time can use Power of Python and it's most powerful AI communities. (Cython, Numba, Pythran, PyPy, OpenMP etc.)

- Implementation for Integrating CoronaLytics with Node-Red

CoronaLytics Dependencies:

If you have a problem about tensorflow-gpu 1.13.1, you can use conda install as bellow:

$ conda install -c nwani tensorflow-gpu

CoronaLytics includes VidGear, a powerful Video Processing engine built with multiple APIs (a.k.a Gears) each with a unique set of trailblazing features. These provides a highly extensible, multi-threaded & asyncio wrapper around many underlying state-of-the-art libraries such as OpenCV, FFmpeg, ZeroMQ, picamera, starlette, pafy and python-mss.

CoronaLytics can grab ultra-fast frames from diverse range of devices/streams, which includes almost any IP/USB Cameras, multimedia video file format (upto 4k tested), various network stream protocols such as http(s), rtp, rstp, rtmp, mms, etc., plus support for live Gstreamer's stream pipeline and YouTube video/live-streams URLs.

Please install VidGear at first as bellow:

$ pip install vidgear


The YOLOv3 trained on COCO is used for person recognition and detection, I have not included the weights as a part of the repository as it is quite big (236MB). You can download it at https://pjreddie.com/media/files/yolov3.weights and add it to the folder - "yolo-coco" as a part of the repository. I have mentioned the folder path on line number 203, and can be changed.

yolopath = "yolo-coco/" # Path points to folder containing weights, cfg and names.


Resources:

Object Detection using YOLO from PyImageSearch
Live Cams videos: Istanbul IBB city live cams https://istanbuluseyret.ibb.istanbul/camera
