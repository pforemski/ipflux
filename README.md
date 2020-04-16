# ipflux

This program will store IPFIX UDP streams in InfluxDB.

Before storing the data, consider the following:
 * switch InfluxDB indexing to TSI,
 * create a data retention policy that will drop old data.
 
If not, your disk and memory will explode in time inversely proportional to your network size :)

# Documentation

See [initial documentation](./ipflux-v1.pdf), a technical report under [the SERIOT project](https://seriot-project.eu/).

# Author

Paweł Foremski, <pjf@foremski.pl>, [@pforemski](https://twitter.com/pforemski)
