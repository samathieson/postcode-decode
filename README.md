# postcode-decode
Retrieves and calculates data on postcodes in England, Scotland and Wales, mainly from Ordnance Survey's OpenSpace API.

This code is designed to be installed on two pages, the first of which is at /postcode-decode/index and the second at /postcode-decode/postcode-decoded. The first is pure PHP, the second can work with just the PHP, but also needs the Javascript if you want to use an Ordnance Survey map.

You can see Postcode-decode working at http://samathieson.com/postcode-decode/ (just the PHP) and at http://samathieson.com/sa-mathieson/data/postcode-decode/ with both the PHP and Javascript, embedded in Wordpress pages. If you want to use it within Wordpress, the PHP can be used through the Allow PHP plug-in and the Javascript through the Raw HTML one.

To make this work however you install it, you need to obtain an Ordnance Survey OpenSpace API key and replace YOURKEYHERE with your key in all three files. You also need to replace YOURURLHERE with your URL in both the PHP files.

The default home location is Trafalgar Square in London. If you want to choose a different home location, you need to alter variables at the start of both of the PHP files: $home (name of home); $homeeast and $homenorth (National Grid co-ordinates of home location); and $homelong and $homelat (longitude and latitude of home location).
