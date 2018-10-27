seawolf.io.service helps user of linux iot devices to get dynamic IP after power up without the needs of monitor, keyboard and mouse. I use it for all my raspberry pi boxes.

Once seawolf.io.service is installed, when the device is powered up again, simply go to http://seawolf.io to get the private IP.

For example: {"hostname": "sam-pi", "wlan0": "10.10.10.103"}

The seawolf.io site saves the data for maxium 6 minutes. It can be accessed only from the same IP where the data is posted from. The access links:

- http://seawolf.io       for human to read
- http://seawolf.io/api   for program to access
- http://seawolf.io/once  delete after being read

Install seawolf.io.service
--------------------------

curl http://seawolf.io/install.txt | bash
