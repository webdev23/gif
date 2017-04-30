# Artistic gif recorder | shell script
Wrapper shell script written in php around byzanz and gifsicle to create fluids optimized GIF's fastly.

<img src="https://i.giphy.com/l1KVaNU6xfgbOmsJq.gif"> <img height="226" src="https://ponyhacks.com/img/www/gif1492819850_merged.gif"> <img width="354" src="https://i.giphy.com/l0Iyh9741gIztjtIc.gif">

Record gif based on mouse position, and can:
- optimize colors
- resize by given pixel width
- reverse frames then merge to original
- upload to giphy, get direct link

Usage: <b>./gif [time in seconds]</b>

Default record time 1 second.

To launch back last settings: <b>./gif !</b> 

Pipe run from sources: <b>php <(curl https://webdev23.github.io/gif/gif)</b>

Dependencies: 

    sudo apt install php xdotool byzanz gifsicle curl

<a href="https://webdev23.github.io/gif/expo.html">See more gif's made with this tool</a>
