[![Slack](https://img.shields.io/badge/Join-Slack-blue)](https://join.slack.com/t/openeew/shared_invite/zt-cibhc0za-XKReMPobi2DsrPusORJZVQ)
[![License](https://img.shields.io/badge/License-Apache2-blue.svg)](https://www.apache.org/licenses/LICENSE-2.0) 
![CCBYSA](https://img.shields.io/badge/License-CC%20BY%20SA%204-blue)


<img src="/images/logo_2020.svg" alt="logo" width="400px"/>



Let's create ***earthquake early-warning (EEW) systems*** for every seismically-vulnerable community in the world!

[OpenEEW](https://openeew.com) is an initiative by [Grillo](https://grillo.io), IBM and Linux Foundation to democratize EEW systems throughout the world by sharing our:
* Entire archive of **unprocessed accelerometer data** from Mexico, Chile and other countries, including earthquakes records with magnitudes above 7 and recorded at different distances 
* **Algorithms for the detection and characterization of earthquakes** in real time
* **Software examples** for creating your own EEW server
* **Hardware designs and firmware** so you can build your own IoT-based seismic sensors
* **Application software** so that users can receive your alerts via mobile apps, devices and more
* **Guidance to help with your project** including deployment of sensors, installations, and more

## What is an Earthquake Early-Warning (EEW) ?
An earthquake early-warning (EEW) system is a set of capacities to detect and characterize a significant earthquake, estimating the distribution of shaking and distribute the information to communities and organizations, enabling individuals to prepare and act appropriately and in sufficient time to reduce the possibility of loss and protect life. 

The alerts are sent in real-time to people before the shaking or the strong part arrives. However, [only some governments have attempted to build EEWs](http://www.unesco.org/new/en/natural-sciences/special-themes/disaster-risk-reduction/geohazard-risk-reduction/early-warning-systems/ip-eews/) due to the incredibly high-cost of traditional seismometers, dedicated telecommunications, and bespoke software.

[Grillo](https://grillo.io) has already demonstrated that an IoT-based approach to EEW systems is not only within the reach of many global citizens, but [performs as well if not better than government-run systems](https://openeew.com/blog/eew-benchmark). 

***OpenEEW*** is a [Call for Code® with The Linux Foundation](https://www.linuxfoundation.org/projects/code-and-response/) project that features a set of core Grillo EEW components; hardware, software and know-how, that will place effective EEWs to be within the reach of many underserved communities around the world.

All OpenEEW projects require the following components:

- **A network of OpenEEW sensors**. You can [build your own](https://openeew.com/docs/build-sensor), [buy here](https://grillo.io/product/openeew-node/), or use someone else's network. 
<img src="/images/openeew-sensor.svg" alt="sensor" width="200"/>

-  **A detection system running on a server**. You can find instructions for deploying your own [here](https://openeew.com/docs/deploy-detection-docker).
<img src="/images/openeew-detection.svg" alt="detection" width="200"/>

- **A method for sending alerts**. For example, to a Twitter account, via [a mobile app](https://openeew.com/docs/build-app), or an IoT device. 
<img src="/images/openeew-alarm.svg" alt="alarm" width="200"/>

## Getting Started
Start by reading this [OpenEEW project website section](http://openeew.com/docs/read-first) which leads to tutorials, guidance and more.

You can also review our [GitHub Discussions forum](https://github.com/openeew/openeew/discussions) and review conversations or start your own thread.

You are also welcome to join our [Slack](https://join.slack.com/t/openeew/shared_invite/zt-cibhc0za-XKReMPobi2DsrPusORJZVQ) for getting to know the community and discussing issues in real-time, including the creation of a network for your region.

## Roadmap
The high level roadmap is as follows:

![Roadmap](https://github.com/openeew/openeew/blob/master/images/openeew-roadmap-v01.svg)

Please refer however to the roadmaps in Github for the main repos:
- [Dashboard roadmap](https://github.com/openeew/openeew-dashboard/projects/1)
- [Detection docker roadmap]()
- [Sensor hardware roadmap](https://github.com/openeew/openeew-sensor/projects/1)
- [Sensor firmware roadmap](https://github.com/openeew/openeew-sensor/projects/2)

## Contributing
Please read [our contributing guidelines](https://openeew.com/docs/contributing) for details of how you can get involved, and [Code of Conduct](CODE_OF_CONDUCT.md) for information about how to participate.

## Authors
* **Grillo** - *Initial work* - [Grillo](https://grillo.io)

Enjoy!  Give us [feedback](https://github.com/openeew/openeew/issues) if you have suggestions on how to improve this information.

## License
This project is licensed under the Apache Software License, Version 2, unless otherwise stated.  Separate third party code objects invoked within this code pattern are licensed by their respective providers pursuant to their own separate licenses. Contributions are subject to the [Developer Certificate of Origin, Version 1.1 (DCO)](https://developercertificate.org/) and the [Apache Software License, Version 2](http://www.apache.org/licenses/LICENSE-2.0.txt).

OpenEEW data on AWS is licensed under CC BY-SA 4.0 (https://creativecommons.org/licenses/by-sa/4.0/).
