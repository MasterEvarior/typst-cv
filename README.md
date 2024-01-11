# typst-cv
This is my CV template. For an example see [here](./cv.pdf).

## Usage
Define most of your information at the beginning
```typst
#let personal_profile = "A very nice text"
#let personal_info = ((
  (
    "service": "email",
    "display": "john@doe.ch"
  ),
  (
    "service": "phone",
    "display": "+1 206 555 0100"
  ),
  ...
))

#show: doc => template(doc, black, "John Doe", "photo.jpeg", personal_profile, personal_info)
```
After that you can use helper functions however you want.


## Icons
You can use whatever icons you want, as long as they are an SVG. Just place them in the `template/assets/svg` folder.

## Images
Place your headshot (or anime avatar, whatever) in the `template/assets/img` folder.