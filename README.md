Eikon-Python
Python: Thomson Reuters Eikon API
Overview:
The Thomson Reuters Eikon API provides simple access to users who require programmatic access to Thomson Reuters data on the desktop. Check out https://developers.thomsonreuters.com/ for more information.

Steps:
1) Download the Eikon package for Python with pip*:
pip install eikon
*If you cannot use pip, you can install the package with wheel (https://pypi.python.org/pypi/eikon)

2) Get your AppID" from the "Application ID Generator" in Eikon (you can find it through the search bar)
3) Import the Eikon Python and set your AppID (while the Eikon is running):
import eikon
eikon.set_app_key('xxxxxxxxxxxxxxxxxxxxxxx')

Requirements:
Python 2.7+ or 3.4+
Eikon Scripting Proxy
EikonID
Release Notes:
-update-
