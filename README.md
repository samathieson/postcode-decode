# postcode-decode
Retrieves and calculates data on postcodes in England, Scotland and Wales, mainly from Ordnance Survey's OpenSpace API.

This code is designed to be installed on two pages, the first of which is at /postcode-decode and the second at /postcode-decode/postcode-decoded. The first is pure PHP, the second also needs the Javascript if you want to use an Ordnance Survey map.

To make this work, you need to obtain an Ordnance Survey OpenSpace API key and add it at the points marked YOURKEYHERE in all three files. You also need to put it your URL at YOURURLHERE in both the PHP files.

If you want to choose a different home location, you need to alter variables at the start of both of the PHP files.
