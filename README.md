# ETL-Project

by Benjamin Aubry, Gary Fisher, and Bruce Mark.
</br>
</br>
</br>
This project was about building a database containing financial data (i.e. historical prices for commodities, Federal Reserve data, and economic event data) that could be used for further data analysis. 

The different data sources as well as data structures (API, Web) led to the creation of a MongoDB which offers flexibility for this type of data storage.  

The database ingests 3 different data sources (see below):
   * www.quandl.com – commodities historical prices (via API)
   * www.stlouisfed.org – Federal Reserve Data (via API)
   * www.forexfactory.com – Economic event calendar (Web-Scraping)
</br>
</br>
The following information explains the steps taken:
</br>

   1. An initial setup needed to take place before performing the ETL process.
      * Generated API keys, installed requirement files, and imported dependencies for quandl.com API and stlouisfed.org API. 
      * Created a .get() request path using BeautifulSoup, analyzed the returned table elements, and decided which were to be extracted from forexfactory.com.





<hr>
<p align="center">
  <img src="Screenshots/MongoDB_economics_db.PNG" alt="drawing" width="700"/>
</p>
<hr>
<p align="center">
  <img src="Screenshots/economics_db.commodities_copper.PNG" alt="drawing" width="500"/>
</p>
<hr>
<p align="center">
  <img src="Screenshots/economics_db.fed_data.PNG" alt="drawing" width="500"/>
</p>
<hr>
<p align="center">
  <img src="Screenshots/economics_db.event_data.PNG" alt="drawing" width="500"/>
</p>
<hr>
