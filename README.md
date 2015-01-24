poocam
======

For a full explanation of this project along with code/video/photos, please visit my blog: http://ruedurivoli.wordpress.com/2014/04/11/poo-cam/

This is my Raspberry Pi surveillance script to capture who was dumping on my yard.  It was a cat!

* A new photo is taken about every 20 seconds.
* A timestamp is embedded into each photo.
* A copy of the file is uploaded to my Dropbox account.
* The oldest file is deleted from the Pi storage as a new photo is added to the website.
* At the end of the day, all the photos from sunrise to sunset, about 2,500, are merged together into a time-lapse video.  Start and end times are placed in a settings file.
* Start and stop times for time-lapse video retrieved dynamically from timeanddate.com.
* The resulting video is uploaded to my YouTube channel.
* An email with the video URL is sent to me.
* Using port forwarding to access the website remotely.
* A start-up script placed into /etc/init.d to automatically start the webcam script when the Raspberry Pi is turned on.
