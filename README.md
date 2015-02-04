<h1> New York State Clean Air Act Permit Parser </h1>

Dependencies: pdftotext (for mac: brew install poppler)

<h4> Background: </h4>
Industrial facilities that emit contaminants to the air in New York State, unless specifically exempted, are required to obtain a Title V permit, a state facility permit, or a registration certificate from the New York State Department of Environmental Conservation as required under the Clean Air Act (CAA). Issued permits become final after a required public notice and comment period and are renewed regularly. These documents hold a variety of information about the facility, including specifics on pollution limitations, controls, and/or monitoring requirements. This information is used every day by organizations, government, researchers, and others to understand a given facility.

NYS CAA permits are housed here: http://www.dec.ny.gov/chemical/32249.html

<h4> Problem: </h4>
These environmental permits hold important information and the data is not accessible in machine-readable format. There is no requirement as of 2015 at the State or Federal level to release data in a usable format. 

<h4> Outline of information to be parsed: </h4>

<ul>permit type</ul>
<ul>dec id</ul>
<ul>permit issued to</ul>
<ul>facility name</ul>
<ul>facility street</ul>
<ul>facility zip</ul>
<ul>facility contact</ul>
<ul>facility description</ul>
<ul>applicable maximum achievable control technology (MACT) standards</ul>
<ul>applicable new source performance (NSPS) standards</ul>
<ul>name of pollutants</ul>
<ul>potential to emit</ul>
<ul>emission units</ul>
<ul>control types</ul>
<ul>monitoring types</ul>
<ul>monitoring frequencies</ul>
<ul>parameters monitored</ul>
<ul>upper permit limits</ul>
<ul>lower permit limits</ul>
