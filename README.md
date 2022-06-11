# rfcscraper
<h1>Scrape RFC's and covert them to PDF or Excel</h1>
<b>Provided as is. I am not a professional developer.</b><br><br>
<b>Note: The PDF converter is much better than the excel. May improve upon this in the future.</b><br><br>

<h2>Use Case:</h2>
<p>This script will take user input of rfc numbers and loop through the input.
Example:
1918 1997

The script will then make a request to find those RFC's and then parse the page and save it to a file for viewing.</p>


<h2>Please make sure you install the rquired pip packages to run the script.</h2>
<li><code>pip install fpdf</code></li>
<li><code>pip install xlsxwriter</code></li>
<li><code>pip install beautifulsoup4</code></li>
Once all requirements are met, run the script. <br>
<li><code>python rfcscrape.py</code></li>
