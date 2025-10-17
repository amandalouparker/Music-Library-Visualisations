# Music Library Visualisations
Data visualisations of personal music libraries
- primarily network graph of artists by similarity in genre

#### Data sources
* Music folder files
* MusicBrainz database https://musicbrainz.org/doc/MusicBrainz_Database
* Spotify API https://developer.spotify.com/documentation/web-api (WIP)

#### Pyviz network graph 
This is a screenshot of the dynamic network graph generated from my library
![Network Graph Image](/NetworkGraphIm.png "Network Graph Image")

#### List of visualisations
* Bubble chart (non-hierarchical) of music genre, volume (size) by song count
* Artist network graph - relationship by genre

* WIP *
* Year of release, timeline (date range of songs and albums, filter by artist or genre)
* Play counts, filter by genre, artist (from spotify or itunes data)

#### How to generate your own music library network graph
1. Install Anaconda (Jupyter notebooks)
2. Open Jupyter notebooks
3. Install all python libraries used, e.g. type !pip install (library name) and run for each library 
4. Run 'Network Graph 1 - get data' notebook to get your own data. Ensure to replace the library pathname, and modify the hobby artist filter (or comment out)
5. Once the ArtistsGenre.csv file is generated run the 'Network Graph 2 - Format data as nodes edges and graph' notebook.
6. Your network graph will be loaded into a new browser tab, and aslo saved as a html file to open and browse later

#### Python libraries used in the network graph
* pandas
* numpy
* musicbrainzngs
* os
* tinytag
* pyvis
    


