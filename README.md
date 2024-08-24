# Face-mask-detection

The new coronavirus that triggered the worldwide pandemic has had a profound impact on every one of our lives. Creating inThe new coronavirus that triggered the worldwide pandemic has had a profound impact on every one of our lives. One way to stop the disease from spreading is to enforce safety precautions like wearing face masks, often washing your hands, and avoiding social situations. Many incidents are caused by public transit every day. Therefore, encouraging individuals to use face masks correctly both before and after boarding the bus will significantly aid in stopping the virus's spread. 

The primary goal of this project is to create a real-time face mask detection system with voice alerts, that can be mounted on public transport systems, enabling passengers to travel in a safe atmosphere free from the worry of contracting the virus.

## Proposed System

![Covid flowchart](https://github.com/user-attachments/assets/1cbca037-859d-4493-813f-5fde971519d9)

We used the pre-trained Deep learning model - MobileNetV2 and trained it on the dataset of people with and without masks. Then used OpenCV and gTTs respectively to feed live stream video to detect the ROI and give voice alerts. 

Once the system was running fine, we configured a camera using raspberry pi camera module, to set up a camera that can take live video stream and provide voice alerts and Light signals(Green - good to go, Red - Not wearing mask or  incorrectly worn)


