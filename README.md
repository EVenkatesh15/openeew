[![Slack](https://img.shields.io/badge/Join-Slack-blue)](https://join.slack.com/t/openeew/shared_invite/zt-cibhc0za-XKReMPobi2DsrPusORJZVQ)
[![License](https://img.shields.io/badge/License-Apache2-blue.svg)](https://www.apache.org/licenses/LICENSE-2.0) 
![CCBYSA](https://img.shields.io/badge/License-CC%20BY%20SA%204-blue)


<img src="/images/logo_2020.svg" alt="logo" width="400px"/>


Let's create ***earthquake early-warning (EEW) systems*** for every seismically-vulnerable community in the world!

OpenEEW is an initiative by [Grillo](https://grillo.io), IBM and Linux Foundation to create a global earthquake early-warning system (EEW). This includes
* Entire archive of **unprocessed accelerometer data** from Mexico, Chile and other countries, including earthquakes records with magnitudes above 7 and recorded at different distances 
* **Algorithms for the detection and characterization of earthquakes** in real time
* **Software examples** for creating your own EEW server
* **Hardware designs and firmware** so you can build your own IoT-based seismic sensors
* **Application software** so that users can receive your alerts via mobile apps, devices and more
* **Guidance to help with your project** including deployment of sensors, installations, and more

## What is an Earthquake Early-Warning (EEW) ?
An earthquake early-warning (EEW) system is a set of technolgies that detect and characterize a significant earthquake, rapidly sending the information to nearby communities, before the shaking arrives, so that they can prepare and act appropriately.

[Only some governments have attempted to build EEWs](http://www.unesco.org/new/en/natural-sciences/special-themes/disaster-risk-reduction/geohazard-risk-reduction/early-warning-systems/ip-eews/) due to the incredibly high-cost of traditional seismometers, dedicated telecommunications, and bespoke software.

![openeeew-diagram](https://github.com/openeew/openeew/raw/master/images/openeew-diagram4.jpg)

[Grillo](https://grillo.io) has already demonstrated that an IoT-based approach to EEW systems is not only within the reach of many global citizens, but [performs as well if not better than some government-run systems](https://openeew.com/blog/eew-benchmark). 

***OpenEEW*** is a [Call for Code® with The Linux Foundation](https://www.linuxfoundation.org/projects/code-and-response/) project that features a set of core Grillo EEW components; hardware, software and know-how, that will place effective EEWs to be within the reach of many underserved communities around the world.

All OpenEEW projects require the following components:

- **A network of OpenEEW sensors**. You can [build your own](https://github.com/openeew/openeew-sensor/tree/master/pcb), or [buy here](https://grillo.io/product/openeew-node/).
<img src="/images/openeew-sensor.svg" alt="sensor" width="200"/>

-  **A detection system running on a server**. We host a [global dashboard](https://dashboard.openeew.com) that monitors everyone's devices and reports events.
<img src="/images/openeew-detection.svg" alt="detection" width="200"/>

- **A method for sending alerts**. For example, to a Twitter account, a mobile app, or an IoT device. 
<img src="/images/openeew-alarm.svg" alt="alarm" width="200"/>

## Getting Started
Start by reading the [Wiki](https://github.com/openeew/openeew/wiki) to get your sensor device up and running.

You are also welcome to join our [Slack](https://join.slack.com/t/openeew/shared_invite/zt-cibhc0za-XKReMPobi2DsrPusORJZVQ) channel and get to know the community, here we discuss issues in real-time.

## Contributing
Please read [our contributing guidelines](https://openeew.com/docs/contributing) for details of how you can get involved, and [Code of Conduct](CODE_OF_CONDUCT.md) for information about how to participate.

## Authors
* **Grillo** - *Initial work* - [Grillo](https://grillo.io)

Enjoy!  Give us [feedback](https://github.com/openeew/openeew/issues) if you have suggestions on how to improve this information.

## License
This project is licensed under the Apache Software License, Version 2, unless otherwise stated.  Separate third party code objects invoked within this code pattern are licensed by their respective providers pursuant to their own separate licenses. Contributions are subject to the [Developer Certificate of Origin, Version 1.1 (DCO)](https://developercertificate.org/) and the [Apache Software License, Version 2](http://www.apache.org/licenses/LICENSE-2.0.txt).

OpenEEW data on AWS is licensed under CC BY-SA 4.0 (https://creativecommons.org/licenses/by-sa/4.0/).
