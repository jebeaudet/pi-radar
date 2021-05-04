# pi-radar
Little project to compute the speed of vehicules with a RTSP camera. My starting point was [this very helpful website](https://www.pyimagesearch.com/2019/12/02/opencv-vehicle-detection-tracking-and-speed-estimation/) and was then modified to polish it a bit and add some specifics about my scenario.

The distance value was calibrated with 3 passages of my car going different speeds.

I initially thought this could run on a raspberry pi but the cpu isn't powerful enough so you need an extra myriad cpu to do it. I instead run it in CPU mode on my 8 core i7 processor with good results.
