# 🗔 Artistic gif recorder | shell script

Create optimised reverse framed gif based on mouse positions, upload to giphy.

Wrapper shell script written in php around byzanz and gifsicle to create fluids optimized GIF's fastly.

<img src="https://i.giphy.com/l1KVaNU6xfgbOmsJq.gif"> <img height="226" src="https://camo.githubusercontent.com/9058bfa14ed33bfa4290c76900309b119bfbc9f7/68747470733a2f2f6d656469612e67697068792e636f6d2f6d656469612f504c497872387063344c5a497361775466702f67697068792e676966"> <img height="226" src="https://media.giphy.com/media/3oKIPnQYrqXZ4wP4lO/giphy.gif">

### Record gif based on mouse position, and can:

- optimize colors
- resize by given pixel width
- reverse frames then merge to original
- upload to giphy, get direct link

### 🖈 Usage: ./gif [time in seconds] 

Default record time 1 second.

    ./gif 10

### 🛦 To launch back last settings

    ./gif !

### 10 seconds fullscreens record with --fullscreen (-f)

    ./gif 10 -f

#### 📡 Without downloading

    php <(curl https://webdev23.github.io/gif/gif)
    
#### 💻 Install as an app, with <a href="https://github.com/webdev23/phi">phi</a>

    php <(curl https://webdev23.github.io/phi/phi) install https://webdev23.github.io/gif/gif

### 🛠 Dependencies: 

    sudo apt install php xdotool byzanz gifsicle curl

<a href="https://webdev23.github.io/gif/expo.html">See more gif's made with this tool</a>
