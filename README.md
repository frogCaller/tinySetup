# tinySetup

<div style="display: flex; gap: 10px;">   
    <img src="Images/tinySetup2.jpg" alt="tinySetup2" width="200">
    <img src="Images/tinySetup3.jpg" alt="tinySetup3" width="200">
</div>


# Materials
* [Raspberry Pi Zero 2 WH](https://amzn.to/4bwP5q9)<br />
* [Micro SD Cards](https://amzn.to/4erXgWD)<br />
* [Waveshare 3.5-in LCD display](https://amzn.to/4bLtsCz)<br />
* [GPIO extender](https://amzn.to/4bGfj9M)<br />
* [Battery pack](https://amzn.to/3R8jWkA)<br />
<br />
(Amazon affiliate links)<br />

# Installations

1. **OS install:**
   - Raspberry Pi Zero 2 WH - Pi OS Lite 32-bit

2. Install 3.5-inch display Driver 
    ```
    git clone https://github.com/goodtft/LCD-show.git
    chmod -R 755 LCD-show
    cd LCD-show/
    ./LCD35-show
    ```

    Rotate screen 180 degrees
    ```
    cd LCD-show/
    ./LCD35-show 180
    ```
   Revert back to HDMI
    ```
    cd LCD-show/
    ./LCD-hdmi
    ```
    
    _[More info](https://github.com/lcdwiki/LCD-show-retropie)_
   
<br />
