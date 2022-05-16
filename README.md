# Mind Place 360 Web App

<img src="https://github.com/Mike-McAnally/Mind-Place-360-Web-App/blob/main/menuImage.jpg">

I've have had a 360 degree camera for a while now. Also, I have a Oculus Quest 2 VR headset (or now Meta Quest 2).

Combining these two pieces of hardware with a tripod, some long video processing time, a webserver, some open source A-frame WebXR, and it is possible to fully capture immersive 360 experiences in virtual reality over the internet. And even share them with others.

Moments whch can be replayed, memories recalled. I call it Mind Place because it helps me remember important events, video logs, and expereinces in my mind and its a data structure in itself, which I am building up slowly over time.

To find out more in a detailed article explaining the code see:

https://michael-mcanally.medium.com/my-360-mind-place-web-app-for-caputuring-immersive-vr-moments-free-open-source-code-295e4f9fbdf0

To see a DEMO example of it in in action:  (best viewed in the Meta Quest 2 browser, or on a desktop in Chrome or FireFox browsers)

https://rocketvirtual.com/MP/indexMike.html

Please note: Be patient! That is because this data is coming over the internet and not preloaded as in a pre-game install. It will take some time to load. 360 data is much larger than 2D data. So imagine a cube with 6 sides, top, bottom and all around. Or imagine an additional axis in the Cartesian coordinate system in three dimensions, so not just x, y, but z-axis as well. The fortunate thing is that caching will occur in the browser after your first load, so impovement of revisitation loading times should actually occur if your browser can cache large file sizes. Otherwise reduce the number of 360 images being downloaded inside each HTML page of the web app to improve the over all wait time for the user experience. I found that eight and less 360 images is about the longest time people are willing to wait for a page to load. Having a fast internet or "intranet/LAN connection" really helps improve the experience.

Here is a zip file of the entire sample structure with audio and video included.  Modify and customize with your own 360 data. https://rocketvirtual.com/MindPlace360App.zip

You can also follow more of my VR projects at https://rocketvirtual.com/
