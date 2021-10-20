# Country-IPLookup
Enter an IP address and find the country that IP is registered in. It also does some processing as to if it is on a private network or not. This tool detects the ISP, City, Region, Country, Latitude and Longitude.

## Description

Enter an IP address and find the country that IP is registered in. It also does some processing as to if it is on a private network or not. This tool detects the ISP, City, Region, Country, Latitude and Longitude. The program is a static command line program that shows the user in a visual fashion what their ISP, City, Region, Country, Latitude and Longitude are.

## Getting Started

### Dependencies

* os, subprocess, json, sys, time, urllib2
```
pip install os, subprocess, json, sys, time, urllib2
```

### Installing

* No real install needed, just make sure you have the bash terminal updated
```
sudo apt update
sudo apt upgrade
```

### Executing program

* Run the program like any other common bash script.
```
python iplocator.py 
```

## Help
Common problems or issues are that you are not using an authorized user and need to switch to root.
```
sudo python iplocator.py
```

## Authors

Contributors names and contact info

Christopher Hyatt (me)
* [@codeslacker1155](https://github.com/codeslacker1155)

## Version History

* 0.2
    * Various bug fixes and optimizations
    * See [commit change]() or See [release history]()
* 0.1
    * Initial Release

## License

This project is licensed under the [GNU Privacy v3] License - see the LICENSE.md file for details

## Acknowledgments

* Inspiration taken from a list of basic programs to make in any language that I have in a random text file of ideas.
