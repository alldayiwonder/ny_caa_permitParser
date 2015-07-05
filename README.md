#New York State Clean Air Act Permit Parser

Dependencies: 
* pdftotext (for mac: brew install poppler)
* pandas

### Background: 
Industrial facilities that emit contaminants to the air in New York State, unless exempt, are required to obtain a Title V permit, a state facility permit, or a registration certificate from the New York State Department of Environmental Conservation. This is required under the Clean Air Act (CAA). Issued permits become final after a required public notice and comment period and are renewed regularly. These documents hold a variety of information about the facility, including specifics on pollution limitations, controls, and/or monitoring requirements. This information is used every day by organizations, government, researchers, and others to understand a given facility and potential impacts to communities and the environment.

NYS CAA permits are housed here: http://www.dec.ny.gov/chemical/32249.html

### Parser:  
These environmental permits hold important information and the data is not accessible in machine-readable format. There is no requirement as of 2015 at the State or Federal level to release data in a usable format. 

This project produces a Python script that reads through each permit and parses important information into machine-readable format.

### Outline of information to be parsed:  

* permit type
* dec id
* permit issued to 
* facility name 
* facility street 
* facility zip 
* facility contact 
* facility description 
* applicable maximum achievable control technology (MACT) standards 
* applicable new source performance (NSPS) standards 
* name of pollutants 
* potential to emit 
* emission units 
* control types 
* monitoring types 
* monitoring frequencies 
* parameters monitored 
* upper permit limits 
* lower permit limits 
