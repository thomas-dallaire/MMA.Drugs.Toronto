README
========================================================

## About
This repo contains the srcipt and data used to create a heat map reflecting the  
probability of various levels of drug abuse by Toronto neighbourhood (based on the results of 
a logisitc regression model using demographic data obtained from the City of Toronto).

## Usage
To reproduce the map, save all of the files into a common folder and open the file `index.html`
in your internet browser.

## Description of `data` file
Each record or row gives:
- The unique area id, `id`. 
- The neighbourhood label, `area`. 
- The the probability of each area being defined as low; medium; or high drug use areas, `xx_low, xx_mid, xx_high`.

## The JSON file
The JSON file 'neighbourhoods.json' is a GeoJson file with the latitude / longitude points 
required to define the boundaries of each neighbourhood in Toronto.
