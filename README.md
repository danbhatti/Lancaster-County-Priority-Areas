# Lancaster-County-Priority-Areas

Isochrones for 19 Priority Areas in Lancaster County, Identified in Places2040

Red and blue isochrones depict 5 and 15 minute walk sheds respectively from Lancaster City and 18 boroughs in Lancaster County. Town centers were selected based on a nearby public amenity (such as a park) or based on the intersection of two major roads defining the boroughs CBD. Walk sheds can help decide where development is most impactful. 

QuickMapServices OpenStreetMap was used with NAD83 / Pennsylvania South (EPGS 2272), which was preferable for the scale we were working at. A point layer was drawn over top of town centers, and ORS Tools Isochones feature was used to plot corresponding isochrones over the point layer. The qgis2web plugin was used to convert this to a webmap.
