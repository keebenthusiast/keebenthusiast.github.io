## About me

I am a Computer Science graduate who achieved a Bachelors in December of 2020.

## Personal Projects

I sort these from newest to oldest. Feel free to drop by my linkedin to see what projects I have done professionally.

I've also done a good amount of tiny projects during my time in college and university, feel free to ask about those if desired.

### kiss-light hub
[repository](https://gitlab.com/kiss-light-project/Kiss-Light_Hub) - Successor to the server, it takes a more modern approach to home automation utilizing mqtt to communicate with wifi-connected goodies that utilize the [tasmota firmware](https://tasmota.github.io/docs/). This hub also uses the kiss-light protocol, though it is slightly adapted for this server and error codes are now documented in the README. The primary aim for this server is to be fairly portable, and also have the ability to run on something as tiny as an Onion Omega2 or as big as a rackmount server. This program will only use the amount of memory it allocates from the initialization stage, and no more. V0.1 is currently deployed on a Raspberry Pi 4, and porting it to an OpenWRT-enabled Linksys WRT1900ACS is currently in the testing phase. The V0.2 release is also around the corner, where it supports even more types of devices and even custom devices.

### kiss-light server
[repository](https://gitlab.com/keebenthusiast/kiss-light) - The original kiss-light project, it utilized the gpio of a typical Raspberry Pi with 40 pins connected to an RF transmitter and Receiver. This project also introduced the kiss-light protocol, an http-inspired protocol which is used to change the saved device's states, add a new device or remove a current device, and list devices currently stored on the server. The v0.5 release replaced the wiringPi libraries with pigpio as wiringPi became deprecated, and is usable if desired. This project was also utilized in my senior project with 5 others where we made an app to communicate with the server.

## Contact

[mail](mailto:cakmf68@outlook.com) | [linkedin](https://www.linkedin.com/in/christian-kissinger-09703b1b4/) | [github](https://github.com/keebenthusiast) | [gitlab](https://gitlab.com/keebenthusiast)
