# smart-meter
HTML page showing graph of Dutch smart meter data

## Preparation
First step is te connect the P1 port of your smartmeter to a computer. Could be a normal desktop, RaspberryPi, Arduino, or whetever you like.
I used the prefabricated cable from this shop: https://sites.google.com/site/nta8130p1smartmeter/webshop

This site also has a Python script to read the P1 information. This script outputs an CSV file.

The project aims at providing a nice graphical graph of the data captured in this CSV file.

## Installation
The installation in 3 easy steps:

1. Make sure the script outputs the CSV files in a directory which is accessible for your HTTP server. 

2. Put the index.html in the same directory.

3. Point your browser to the directory.

Done !
