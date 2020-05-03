This repository includes two modules

# Embedding tiff into HTML canvas

Using this module any tiff can be uploaded and embedded into html Canvas.

1. Spin off http server using this command in root directory: 
*http-server -a localhost -p 8000 -c-1*

2. Navigate to tiffcanvas.html in browser 


# Render mbtiles on map based html file 

This module takes mbtiles and does indexing before rendering it to map.
renderTileOnMap.sh script is used for that purpose 

1. Make script executable: 
  *chmod +x renderTileOnMap.sh*
  
2. Provide mapbox access token using: 
  export MAPBOX_ACCESS_TOKEN=*your_mapbox_access_token*
  
3. Run script:  
   *./renderTileOnMap.sh*
   
This will render mbtiles on map in browser, by default on port 3000


