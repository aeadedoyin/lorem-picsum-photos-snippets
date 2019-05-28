# Lorem Picsum photos snippets

Visual studio code snippets extension for [Lorem Picsum](https://picsum.photos/).

- Quick way to create an `img` tag with `src` attribute target to a Lorem Picsum photo in HTML files by typing `picsum`.
- Support snippets for CSS background image with Lorem Picsum photos in CSS file by typing `picsum`.
- Support snippets for requesting image list of picsum photos in JavaScript file by typing `picsum.xhrHttpRequest` or `picsum.axiosHttpRequest`.

## Usage

To use the snippets, open a HTML or CSS file, and start typing with `picsum`.

## Quick Start

![](https://i.imgur.com/ncYcqdC.gif)
Type `picsum` to get an image.

![](https://i.imgur.com/4XZJFUf.gif)
Type `picsum-grayscale` to get an image with grayscale effect.

![](https://i.imgur.com/4Q8H5bO.gif)
Type `picsum-blur` to get an image with blur effect.

![](https://i.imgur.com/wqPoiLG.gif)
Type `picsum-adorable-dog` to get an adorable dog image.

## Features

Trigger | Description
--- | ---
picsum | Get a image with specific ID, width and height.
picsum-square | Get a square image
picsum-grayscale | Get a image with grayscale effect
picsum-blur | Get a image with blur effect
picsum-grayscale-blur | Get a image with grayscale and blur effect
picsum-facebook-og-image | Get meta tag with [facebook open graph image size(1200x630px)](https://www.h3xed.com/web-and-internet/how-to-use-og-image-meta-tag-facebook-reddit)

### Get specific image

Trigger | Description
--- | ---
picsum-bear | Get a bear image
picsum-adorable-dog | Get a adorable dog image
picsum-peaceful-lake | Get a peaceful lake image
picsum-city-view | Get a city view image
picsum-escalator | Get a escalator image
picsum-sport-venue | Get a sports venue image
picsum-city-sunset | Get a city sunset image
picsum-vase | Get a vase image
picsum-wheat | Get a wheat image
picsum-traveler | Get a traveler image
picsum-valley | Get a valley image

#### People

Type `picsum-people-${num}`

for example: `picsum-people-5`

![](https://i.imgur.com/gU8zAuz.gif)

#### Building

Type `picsum-building-${num}`

for example: `picsum-building-3`

![](https://i.imgur.com/esELlYD.gif)

#### Mountain

Type `picsum-mountain-${num}`

for example: `picsum-mountain-1`

![](https://i.imgur.com/rY2JdBM.gif)

#### Road

Type `picsum-road-${num}`

for example: `picsum-road-4`

![](https://i.imgur.com/M0eoufS.gif)

#### Vehicle

Type `picsum-vehicle-${num}`

for example: `picsum-vehicle-2`

![](https://i.imgur.com/vj9amYB.gif)

#### Boat

Type `picsum-boat-${num}`

for example: `picsum-boat-1`

![](https://i.imgur.com/qKBwqjD.gif)

### Image list

### XHR HTTP request

Get a XHR HTTP Request for an image list in JavaScript file.

1. Type `picsum.xhrHttpRequest`.
![](https://i.imgur.com/hpCC2fd.png)

2. Then you will get a XHR HTTP request flow for an image list from Lorem Picsum.
![](https://i.imgur.com/U1qHRRG.png)

### Axios request

1. Type `picsum.axiosHttpRequest`.

2. Then you will get a axios HTTP request flow for getting an image list from Lorem Picsum.