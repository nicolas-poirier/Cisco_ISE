# ise_get-endpoints-info.py

Export desired endpoints from Cisco ISE Server to a ready to import csv

#### Prerequisites
* Cisco ISE Server
  * Release: 1.2.x
* Python
  * Version 3.x
  
 - On Linux and MacOS, it may be needed to use the python3 command to specify the version of Python
- System Args
  * Help section:
```
$ python ise_get-endpoints-info.py --help
usage: ise_get-endpoints-info.py [-h] --ise ISE -u USER -p PASSWORD
                                 [-f FILTER]

Export desired endpoints from Cisco ISE Server to a ready to import csv

optional arguments:
  -h, --help            show this help message and exit
  --ise ISE             IP Address or FQDN of ISE Server
  -u USER, --user USER  username to authenticate on ISE
  -p PASSWORD, --password PASSWORD
                        password to authenticate on ISE
  -f FILTER, --filter FILTER
                        collect info only for endpoint groups containing this
                        (optional)
```

## Authors & Maintainers

* Nicolas Poirier
  * Twitter: [@NicolasPoirie19](https://twitter.com/NicolasPoirie19)
  * LinkedIn: [Nicolas Poirier](https://www.linkedin.com/in/nicolas-poirier-fr)
  * Website: [wifiblog.fr](https://wifiblog.fr)

## License

This project is licensed to you under the [GNU General Public License v3.0](./LICENSE).
