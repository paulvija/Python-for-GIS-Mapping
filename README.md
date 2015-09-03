# Python-for-GIS-Mapping

####WMS Overlay

Add WMS as an overlay to the folium map.
For mapping New Zealand define min/max longitude to capture past 180 degrees.

####PySAL to read shapefile data(.dbf)
Easy to read shapefile data(.dbf) using PySAL and store it in Pandas dataframe for easy plotting. 

####Pyshp to write shapefile from a Comma Seperated Values file (csv)
Used Pandas to read the CSV file and row by row. Populate shapefile point & records with in the for loop while iterating. Used a reasonably long csv file with 11,000 rows & 5 columns, noticed it took only few seconds to run.
