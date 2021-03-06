# Responsive Grid Layout Template #

I was too lazy to copy the CDN's for Bootstrap every time I wanted to use it, plus I was really only using the built in layout system anyways.

So I asked myself: "how hard could it really be to make my own responsive grid layout without all the fluff?"

Turns it out it isn't too hard.

## Documentation ##

1. wrap each row in a `<div class='row'>`
1. the number of columns should never exceed 12
1. `<div class='col-n'>` where n is a number > 1 and < 12, creates a block of size n
1. `<div class='col-s-n'>` where n is a number > 1 and < 12, creates a block of size n tailored towards tablet devices

## Browser Support ##

Based on my research (no testing yet), this CSS template will work in the following browsers:

| Browser Name  | Version No.   |
| ------------- |:-------------:|
| Chrome        | 52 |
| Firefox       | 57     |
| IE            | 11      |
| Edge          | 14      |
| Safari        | 10.1     |
| Opera         | 44     |

## Release Notes ##

* Version 1.0.0
  * Initial upload
* Version 1.1.0
  * Added minified CSS
  * Added documentation
