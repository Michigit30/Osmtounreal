# Osm to unreal
Download the osm_builder_1.zip and add it as a plugin in Blender  
Press N, go to OSM Builder, enter the latitude and longitude as well as the radius in meters, then press the button OSM Data Load and wait until everything has loaded.  
Then go to Buildings to generate the buildings.  
Do the same with Roads and Vegetation & Trees.  
Alternatively, you can also upload your own assets.
After that, go to Save as JSON. If you go with the JSON, go to https://jsonconvertertounreal.netlify.app/ and upload it there, or alternatively use the index.html and download the converted file. Next, go into Unreal Engine 5 and go to Output Log, there you paste the code from inportcodepython.txt (first change the path in the code (line 74): json_file_path = r"C:Path/Untitled_roads_only.json"). Make sure that you have activated the "Python Editor Script Plugin" under Plugins and that the Output Log is in Python mode, then press enter and the splines will be spawned. Then go to "List of world Blueprints available to the user for editing or creation" and then to Convert Selection to Blueprint Class… and choose one of the three options so that in the end it is a Blueprint.
