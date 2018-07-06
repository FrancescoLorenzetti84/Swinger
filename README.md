# Swinger
A JQuery plugin to create animations that follow the movement of the cursor

## Usage

Simply wrap each image into a container, in the right order you want the animation to be executed

    <div class="swinger-container">
        <img src="1.jpg" />
        <img src="2.jpg" />
        <img src="3.jpg" />
        <img src="4.jpg" />
        <img src="5.jpg" />
        <img src="6.jpg" />
        <img src="7.jpg" />
    </div>

Then call the plugin

    $(".swinger-container").swinger();
