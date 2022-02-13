# yt
A simple bash script that searches and plays YouTube videos.  
Dependencies: [`mpv`](https://mpv.io), [`pup`](https://github.com/EricChiang/pup) and [`dmenu`](https://tools.suckless.org/dmenu/)
  
 ## How it works
 This script scrapes search results from an [Invidious](https://invidio.us) (currently set to [yewtu.be](https://yewtu.be)) instance using `pup` and displays them in `dmenu`. It then loads up `mpv` with the video selected by the user.
