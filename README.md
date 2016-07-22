# k8s-on-pi

Run Kubernetes on a Raspberry Pi Cluster.

# Hardware
I found the basic shopping list here:
http://blog.kubernetes.io/2015/11/creating-a-Raspberry-Pi-cluster-running-Kubernetes-the-shopping-list-Part-1.html

The only modification I made was to go up to the Raspberry Pi 3 Model B:
https://www.adafruit.com/products/3055?gclid=CPHw86Oph84CFYwfhgodFHEIKQ

# Since I'm using different hardware ...
Some of the other bits didn't work. Here's what I needed to do:

1. Use the hypriot flash tool to flash a linux with Docker image on your flash drives: https://github.com/hypriot/flash
2. Check out the hypriot downloads page for the most recent, but I used: https://downloads.hypriot.com/hypriotos-rpi-v0.8.0.img.zip
3. Install kubernetes on RaspberryPi from these instructions: https://github.com/Project31/kubernetes-installer-rpi

This will give you a little older version of RaspberryPi. I'm currently looking into how to get the recent version working.
