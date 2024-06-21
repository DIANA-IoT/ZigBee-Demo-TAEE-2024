# ZigBee Demo TAEE 2024

### Code repository for the article entitled "WSAN ZigBee demonstrator based on commercial home automation devices and development platforms"

Related work:

Castillo-Sánchez J.B, Cano-García J.M, González-Parada E., Maestre-Nadal M.: *WSAN ZigBee demonstrator based on commercial home automation devices and development platforms* - XVI International Conference of Technology, Learning and Teaching of Electronics, 2024

**The structure of the repository is as follows:**
```
ZigbeeDemoTAEE2024
├── envio_bmi160
├── recibo_bmi160
├── LICENSE
``````
Both folders implement a custom ZigBee cluster to communicate each other the updates of a BMI 160 accelerometer data. <br>
Project *envio_bmi160* interfaces with the sensor whereas *recibo_bmi160* displays on a LCD screen the gathered data. 

Hardware used: 2x Nordic Semiconductors nRF5340 DK + 1 BMI 160 + LCD. <br>
Software version nRFConnect SDK v.2.4.0.


## Credits

This software was actively developed and contributed by:
 - José Manuel Cano García
 - José Borja Castillo Sánchez
 - Eva González Parada
 - Manuel Maestre Nadal

All members are affiliated at [University of Malaga](https://www.uma.es/), department of Electronic Techonology and [Malaga Telecommunications Research Institute](https://www.telma.uma.es/).

## Copyright and License

This software is distributed under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This package is at Copyright (c) University of Malaga. This copyright information is specified in the headers of the corresponding files.

## Acknowledgements

This work has been supported by project TED2021-
130456B-I00, funded by MCIN/AEI/10.13039/501100011033
and EU ”NextGenerationEU/PRTR” program and the Malaga
University project B4-2023-12.