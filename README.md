# yt
A simple bash script that searches and plays YouTube videos.  
Dependencies: [`mpv`](https://mpv.io), [`pup`](https://github.com/EricChiang/pup) and [`rofi`](https://github.com/davatorium/rofi)  
  
 ### Wayland support  
 Works with the package `rofi-wayland` on Fedora repos.
  
 ## How it works
 This script scrapes search results from an [Invidious](https://invidio.us) (currently set to [yewtu.be](https://yewtu.be)) instance using `pup` and displays them in `rofi`. It then loads up `mpv` with the video selected by the user.
