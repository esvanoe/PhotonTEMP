# PhotonTEMP
Temp and Humidity sensor using a Particle Photon and a DHT11 sensor. 

Reports the data via a GET request using three variables to transmit the unit's assigned ID, and the temp and humidity.

Relies on httpclient.h as an import but nothing else.

Uses about 1/3 of the flash on the Photon board, as of 2019.

Easily flashed from build.particle.io and have not tried flashing via. Arduino SDE yet.


