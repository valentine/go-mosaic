# Go-Mosaic

Go-Mosaic is a mosaic creator written in Go.

This was written as an entry for [Go Challenge 3](http://golang-challenge.com/go-challenge3/).

## Installation

    go get github.com/valentine/go-mosaic/

## Usage

    go-mosaic -input="input.jpg" -output="output.jpg" source="photodirectory" -tile=16    
    
**input**: Path of input image (used to create mosaic)

**output**: Path of output image (defaults to **output.jpg**)

**source**: Directory for source images (defaults to **photos/**)

**tile**: Size of tiles in output image (higher numbers process faster, but images will have less resolution) (defaults to **16**)

## Example

### Input
![input image](https://github.com/Valentine/go-mosaic/raw/master/example/input-yosemite-s.jpg "Input Image")
[Original file](https://www.flickr.com/photos/stankus/14739432307/) — 5,616 x 3,744 (23.2MB)

### Output

#### Default tile setting (tile=16)
![output image](https://github.com/Valentine/go-mosaic/raw/master/example/output-yosemite-s16.jpg "Output Image")
This took 88 minutes to generate on a 2013 MacBook Pro — [100% crop of output image](https://github.com/Valentine/go-mosaic/raw/master/example/output-yosemite-s16-full.jpg)

#### Custom tile setting (tile=32)
![output image](https://github.com/Valentine/go-mosaic/raw/master/example/output-yosemite-s32.jpg "Output Image")
This took 29 minutes to generate on a 2013 MacBook Pro — [100% crop of output image](https://github.com/Valentine/go-mosaic/raw/master/example/output-yosemite-s32-full.jpg)

## Licence

Code licensed under The MIT License (MIT).

Images used in the examples are property of their respective copyright owners, and are for educational purposes only.