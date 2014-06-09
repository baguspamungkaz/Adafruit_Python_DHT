Adafruit Python DHT Sensor Library
==================================

Python library to read the DHT series of humidity and temperature sensors on a Raspberry Pi or Beaglebone Black.

Designed specifically to work with the Adafruit DHT series sensors ----> https://www.adafruit.com/products/385

For all platforms (Raspberry Pi and Beaglebone Black) make sure your system is able to compile Python extensions.  On Raspbian or Beaglebone Black's Debian/Ubuntu image you can ensure your system is ready by executing:

````
apt-get update
sudo apt-get install build-essential python-dev
````

On a Raspberry Pi this library depends on the following library:

-   [bcm2835](http://www.airspayce.com/mikem/bcm2835/)
    
    -   Install the library by following these steps:
        
        ````
        wget http://www.airspayce.com/mikem/bcm2835/bcm2835-1.36.tar.gz
        tar zxvf bcm2835-1.36.tar.gz
        cd bcm2835-1.36
        ./configure
        make
        sudo make install
        ````

On a Beaglebone Black there are no other dependencies.

Install the library by downloading with the download link on the right, unzipping the archive, and executing:

````
sudo python setup.py install
````

See example of usage in the examples folder.

Adafruit invests time and resources providing this open source code, please support Adafruit and open-source hardware by purchasing products from Adafruit!

Written by Tony DiCola for Adafruit Industries.

MIT license, all text above must be included in any redistribution