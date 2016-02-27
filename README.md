# Buonconsiglio
Potree Viewer for Buonconsiglio Dataset

This is the code for the modified Potree Viewer used for visualising the data collected in .
Potree viewer version 1.4 RC

Only the castle aerial point cloud and the torre Aquilla point cloud are included for visualisations purposes
The rest of the point clouds can be found in OwnCloud in the folder "Potree Point Clouds". Point Cloud Folders:
1.castleEast
2.castleWest
3.door
4.door2
5. walls_outside


The pointclouds have been converted with the Potree Converter from Laz files. In order to add other point clouds they have to be converted too. 

How to make it work!:

1. Copy All the folders into your [local] server
2. Use the link [http://localhost:8888/]Buonconsiglio/Castle/examples/castle.html to view
3. To add more point clouds copy the Point Cloud Folders to Buonconsiglio/Castle/resources/pointclouds/
4. Activate the respective lines of code in castle.html file (lines 122-126) or create a new link to a new point cloud. The layer/checkbox for the each point cloud is automatically created. 
5. Currently there is only one hotspot on the Torre Aquilla - more to come soon!
