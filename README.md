TitaniumWithoutStudio
=====================

Base projects of Titanium HelloWorld that can be run with out Titanium Studio

a) TestHello is the Android project which has internal references to other Titanium Library Projects
The library projects can be downloaded from the Titanium Source at this location
https://github.com/appcelerator/titanium_mobile/tree/master/android

b) TitaniumHello is the Android project which has references to the jars & .so files 
Jars contained inside the project are fetched from here 
C:\Users\USERNAME\AppData\Roaming\Titanium\mobilesdk\win32\3.1.3.GA\android
C:\Users\USERNAME\AppData\Roaming\Titanium\mobilesdk\win32\3.1.3.GA\android\native\libs



Additional Info:
Inorder to create this sample project, a Titanium project was first converted to an Eclipse Project using ti_eclipsify python scripts from this page
https://github.com/billdawson/tidevtools/blob/master/

Modify tidevtools_settings.py file to include following line
TIMOBILE_SRC = 'C:\Users\USERNAME\AppData\Roaming\Titanium'

Modify ti_eclipsify.py to have path mentioned of android titanium source as follows:
sys.path.append(os.path.join(TIMOBILE_SRC, "mobilesdk","win32","3.x.x.GA", "android"))

