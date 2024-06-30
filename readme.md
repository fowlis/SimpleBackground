### Simply adds a background image to the Discord app while keeping the Discord feel. 
## Preview
<img src="preview.png">

## Usage
```css
@import url("https://fowlis.github.io/SimpleBackground/main.css");

:root {
    --background: url('https://i.imgur.com/rn0AlMm.jpg'); /** replace the URL with your desired image */
    --chat-transparency: 0.8; /** transparency of the main chat area */
    --sides-transparency: 0.9; /** transparency of server list, channel list & member list */
    --sides-blur: 5px; /** blur of background behind the server list, channel list & member list */
}
```

Copy the above to your CSS editor.

Make sure the `@import` line is at the *top* of the editor, else it won't work. You can put the `:root {}` lines anywhere else.
### BetterDiscord
The CSS editor can be found at __Settings > Custom CSS__
### Vencord
The CSS editor can be found at __Settings > Themes > Edit QuickCSS__

## Customisation
Changing the background image is as simple as changing the image URL at the `--background` variable.

If you do not have a URL for your image, upload it to [Imgur](https://imgur.com), then right click the image and select "Copy Image Link".

The `--chat-transparency` and `--sides-transparency` have a minimum and maximum of 0 and 1 - you can choose any decimal between those numbers.

`--sides-blur` can be any blur value you wish.