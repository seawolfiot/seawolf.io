seawolf.io is a service provided by Seawolf Technologies Inc. It is free and open source. It helps users of linux powered devices to get dynamic IP after power up without the needs of monitor, keyboard and mouse.

Once seawolf.io.service is installed, whenever the device is powered up again, simply go to https://seawolf.io to get the private IP.

For example: {"hostname": "sam-pi", "wlan0": "10.10.10.103"}

The seawolf.io site keeps the data for maxium 10 minutes. It can be accessed only from the same IP where the data is posted. The access links:

- https://seawolf.io           for human to read
- https://seawolf.io/get       for program to access
- https://seawolf.io/get/once  delete after being read

Install seawolf.io.service
--------------------------

curl -s https://seawolf.io/install | bash

OR use github directly

curl -s https://raw.githubusercontent.com/seawolfiot/seawolf.io/master/install | bash

Licensing
---------

<a href="https://opensource.org/licenses/MIT">MIT License</a>
