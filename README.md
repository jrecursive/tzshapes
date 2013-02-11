tzshapes
========

* timezone shapes derived from data from http://efele.net/maps/tz/world/

* tsv fields as follows:

	id	X-Coordinate	Y-Coordinate	Z	M	TZID
	0	-61.29474258	 15.54288101	0	0	America/Dominica	
	0	-61.28013611	 15.53450775	0	0	America/Dominica	
	0	-61.27641678	 15.52553082	0	0	America/Dominica	
	0	-61.27836990	 15.51774502	0	0	America/Dominica	
	0	-61.27744675	 15.51475430	0	0	America/Dominica	
	0	-61.27320862	 15.51196861	0	0	America/Dominica	
	0	-61.26540756	 15.51099110	0	0	America/Dominica	
	0	-61.26282120	 15.50890541	0	0	America/Dominica	
	0	-61.26195145	 15.49880219	0	0	America/Dominica	
	
	...

	27734	-111.91568756	 27.06038857	0	0	America/Mazatlan	
	27734	-111.91547394	 27.05460930	0	0	America/Mazatlan	
	27734	-111.91708374	 27.05118942	0	0	America/Mazatlan	
	27734	-111.92748260	 27.04515839	0	0	America/Mazatlan	
	27734	-111.93288422	 27.04478836	0	0	America/Mazatlan	
	27734	-111.93438721	 27.04688072	0	0	America/Mazatlan	
	27734	-111.92853546	 27.05666542	0	0	America/Mazatlan	
	27734	-111.92071533	 27.06205177	0	0	America/Mazatlan	
	27734	-111.91728210	 27.06311989	0	0	America/Mazatlan	
	
* from http://efele.net/maps/tz/world/

The tz_world shapefile captures the boundaries of the TZ timezones across the world, as of TZ 2012c. The geometries are all POLYGONs, and a TZ timezone will sometimes have multiple polygons. There are about 28,000 rows.

The tz_world_mp shapefile captures the same boundaries. The geometries are either POLYGONs or MULTIPOLYGONs, and there is a single geometry for each TZ timezone. There are 394 rows.



