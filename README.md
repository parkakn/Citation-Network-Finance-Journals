# Web-scraping citations data and constructing a citation network 

We build a web-scraping program to collect publication data of papers published on the Journal of Financial Economics (JFE) for the past 15 years and the citation data of papers that cite these JFE papers on Google Scholar. 

First, our web-scraping program collects the citation data parsing by parsing through the html code of the websites that contain the information of our interest. 

<p align="center">
  <img alt="Dark" src="Images/jfe_site.png" width="45%"> 
&nbsp; &nbsp; &nbsp; &nbsp;
  <img alt="Light" src="Images/gs_citation_ex.png" width="45%">
</p>

Then, we build the citation network where the nodes are the cited JFE papers and the Google Scholar citing papers and the edges are paper-to-paper citations. 

Using the HoloViz package, we visualize our citation network. Drawing our network allows us to visually spot significant papers based on their connectivity in the network. 

<p align="center">
  <img alt="Dark" src="Images/citation_network_plot.png" width="100%"> 
</p>