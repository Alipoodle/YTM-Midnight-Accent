# YouTube Music Midnight Accent
Adding some Accent colours to to YouTube Music and makes it feel a bit like Google Play Music. RIP.

## Things you need to do.
- Open up the file and import the content into something like Stylus, Stylish, Youtube Music Desktop App or Something else.
- Do a Find and Replace for the Colour of `#0d47a1` and Replace it with the Hex Value of your Choice
- Do a Find and Replace for the RGB of `13, 71, 161` and Replace it with the RGB Value of your Choice.

### Customise YouTube Logo:
- Go to Google and Search `Color Picker`
- Input the Colour of your Choice.
- Notice the far right there is a HSL options.

- At this section of the code, use the first Comma for the `hue-rotate` and second value as a decimal of 1 in the `saturate`
```css
.logo.ytmusic-nav-bar {
    /* This will need some tweeking depending on the user's colour */
    filter: hue-rotate(216deg) saturate(0.85);
```
- I.E. Given the existing colour #0d47a1. Google will return a HSL of `216°, 85%, 34%`

   In the `hue-rotate` we place the `216`, and in the `saturate` we do `0.85`

----------

## Features
- Allows for you to change the YouTube Red into a Colour of your Choice
- Adds a few more uses of the Accent Colour.
- Colour Navigation bar on Scrolling down
- Swaps layout of Bottom bar to Music - Controls - Additional Controls
- Adds a Coloured ring around the Pause/Play Icon
- Increases size of Album art in Queue.

## Screenshots

### Main Screen
![Main Screen](https://i.imgur.com/bZSKam0.png)

### Queue
![Queue](https://i.imgur.com/f03HjKE.png)

