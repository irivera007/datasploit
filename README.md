[![ToolsWatch Best Tools](https://www.toolswatch.org/badges/toptools/2016.svg)](https://www.toolswatch.org/2017/02/2016-top-security-tools-as-voted-by-toolswatch-org-readers/)

[![Black Hat Arsenal](https://www.toolswatch.org/badges/arsenal/2016.svg)](https://www.blackhat.com/us-16/arsenal.html#datasploit) US

[![Black Hat Arsenal](https://www.toolswatch.org/badges/arsenal/2016.svg)](https://www.blackhat.com/us-16/arsenal.html#datasploit) EU




# Overview of the tool:
* Performs OSINT on a domain / email / username / phone and find out information from different sources.
* Correlates and collaborate the results, show them in a consolidated manner. 
* Tries to find out credentials, api-keys, tokens, subdomains, domain history, legacy portals, etc. related to the target. 
* Use specific script / launch automated OSINT for consolidated data.
* Performs Active Scans on collected data.
* Generates HTML, JSON reports along with text files.
 
## Basic Usage:
```

	  ____/ /____ _ / /_ ____ _ _____ ____   / /____  (_)/ /_
	  / __  // __ `// __// __ `// ___// __ \ / // __ \ / // __/
	 / /_/ // /_/ // /_ / /_/ /(__  )/ /_/ // // /_/ // // /_  
	 \__,_/ \__,_/ \__/ \__,_//____// .___//_/ \____//_/ \__/  
	                               /_/                        
						
         	   Open Source Assistant for #OSINT            
                 website: www.datasploit.info               
	
Usage: domainOsint.py [options]

Options:
  -h,	    	--help			    show this help message and exit
  -d DOMAIN,	--domain=DOMAIN		Domain name against which automated Osint 
                                    is to be performed.

```

# Required Setup:
* Python 2.7 (because bunch of dependencies do not support Python 3.0)
* Bunch of python libraries (use requirements.txt)


## Detailed Tool Documentation:
> [http://datasploit.readthedocs.io/en/latest/](http://datasploit.readthedocs.io/en/latest/)

## Up and Running Datasploit GUI
```
    pip install -r requirements.txt
    python manage.py collectstatic
    python manage.py makemigrations
    python manage.py migrate
    python manage.py runserver

```

![alt text](https://raw.githubusercontent.com/anandtiwarics/datasploit/master/GUI%20Photos/datasploit.PNG)


![alt text](https://raw.githubusercontent.com/anandtiwarics/datasploit/master/GUI%20Photos/shodan.png)


![alt text](https://raw.githubusercontent.com/anandtiwarics/datasploit/master/GUI%20Photos/subdomain.png)


![alt text](https://raw.githubusercontent.com/anandtiwarics/datasploit/master/GUI%20Photos/wikileaks.png)


