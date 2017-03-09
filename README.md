# smart-meter
HTML page showing graph of Dutch smart meter data

## Preparation
First step is te connect the P1 port of your smartmeter to a computer. The computer could be a normal desktop, RaspberryPi, Arduino, or whetever you like. For the cable, I used the prefabricated cable from this shop: https://sites.google.com/site/nta8130p1smartmeter/webshop

Their site also has a Python script to read the P1 information. This script outputs an CSV file.

This project aims at providing a nice graph of the data captured in this CSV file, in your browser using an HTTP server on the connected computer.

## Installation
The installation has only 3 easy steps:

1. Fire up the script and make sure it outputs the CSV files in a directory which is accessible for your HTTP server. 

2. Put the index.html in the same directory.

3. Point your browser to the directory.

Done !
