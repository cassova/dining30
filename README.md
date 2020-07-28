# JCB Dining30 on Google Maps
JCB Platinum and Gold card members have access to 30% discounts at select restaurants around Japan. The data is presented via website in tabular form. This project scraps the data, translates it to English and plots it on Google Maps to make it easier to browse.

I started this based on the code from https://towardsdatascience.com/how-to-web-scrape-with-python-in-4-minutes-bc49186a8460

The dining30 website: https://pr.gnavi.co.jp/promo/jcb-dining30/restaurant/list.php?page=1

To use:

In order for this to work for you, you must first login with a Google Chrome browser to the Dining30 dining list (via JCB login and hosted on https://pr.gnavi.co.jp/).  This will ensure Google Chrome has access to active cookies that can be used by the driver to scrap the website.

You'll also need a Google Cloud Account with billing enabled to get an API key to the necessary services.  Store your API key in a file called `gmap_api.key` in the same folder as this notebook. The API key should have the Google Maps, Google Places and Google Geocodes APIs enabled.  Check these resources for more information:
 - https://developers.google.com/maps/documentation/javascript/overview
 - https://developers.google.com/places/web-service/overview
 - https://developers.google.com/maps/documentation/geocoding/overview
 
This is an excellent source on how to interact with the Maps API within Python: https://buildmedia.readthedocs.org/media/pdf/jupyter-gmaps/latest/jupyter-gmaps.pdf
