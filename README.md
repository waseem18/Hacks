Hacks
============
A Linux terminal client to find upcoming Hackathons near you or at a particular location.

[![Build Status](https://travis-ci.org/waseem18/Hacks.svg?branch=master)](https://travis-ci.org/waseem18/Hacks)
[![Join the chat at https://gitter.im/waseem18/Hacks](https://badges.gitter.im/waseem18/Hacks.svg)](https://gitter.im/waseem18/Hacks?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

Installation
--------------
1. Clone the repository
    ```sh
    git clone https://github.com/waseem18/hacks.git && cd hacks
    ```

2. Copy the `hacks` executable into your PATH
    ```sh
    cp hacks /usr/local/bin
    ```

Commands
--------
```
hacks                                 Outputs details of Hackathons in or near your current location.
hacks [location]                      Outputs details of Hackathons in or near [location]
hacks --all                           Outputs details of Hackathons all over the World.
```
Examples
--------
```
hacks
hacks California
hacks New York
hacks Canada
hacks Hyderabad
hacks --version
hacks --help
hacks --all
```

Note
--------
Details of Hackathons have been taken from

1. [Hackalist](http://www.hackalist.org)
2. [Hackathon-Calendar](https://github.com/japacible/Hackathon-Calendar)
3. [HackathonWatch](http://www.hackathonwatch.com)
4. [Hackathons-In-India](https://github.com/waseem18/Hackathons-In-India)



Contributions
---------------
1. If you know about any upcoming hackathons, add it to [Hackathon-Calendar](https://github.com/japacible/Hackathon-Calendar). If hackathon is particularly from India, add it to [Hackathons-In-India](https://github.com/waseem18/Hackathons-In-India)
2. Contribute to this repository by removing bugs, improving code efficiency, adding new sources of hackathons etc. I will happily merge it :)
