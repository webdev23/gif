# 🗔 Artistic gif recorder | shell script

Create optimised reverse framed gif based on mouse positions, upload to giphy.

Wrapper shell script written in php around byzanz and gifsicle to create fluids optimized GIF's fastly.

<img src="https://i.giphy.com/l1KVaNU6xfgbOmsJq.gif"> <img height="226" src="https://ponyhacks.com/img/www/gif1492819850_merged.gif"> <img height="226" src="https://media.giphy.com/media/3oKIPnQYrqXZ4wP4lO/giphy.gif">

### Record gif based on mouse position, and can:

- optimize colors
- resize by given pixel width
- reverse frames then merge to original
- upload to giphy, get direct link

### Usage: ./gif [time in seconds] 

Default record time 1 second.

    ./gif 10

### To launch back last settings

    ./gif ! 

#### Without downloading

    php <(curl https://webdev23.github.io/gif/gif)
    
#### Install as an app, with <a href="https://github.com/webdev23/phi">phi</a>

    php <(curl https://webdev23.github.io/phi/phi) install https://webdev23.github.io/gif/gif

### Dependencies: 

    sudo apt install php xdotool byzanz gifsicle curl

<a href="https://webdev23.github.io/gif/expo.html">See more gif's made with this tool</a>
