# PyWaveThermo

Forked from robintw/pywavethermo

This is Python code to connect to and control the Worcester Wave thermostat
(a wifi-connected 'Smart Thermostat' that seems to be based on - or even the same as - the NeFit thermostat).

Full information is available on my blog (start at http://blog.rtwilson.com/hacking-the-worcester-wave-thermostat-in-python-part-1/),
but the `example.py` file should be fairly self-explanatory. The only requirement is the sleekxmpp module.

MP notes

Need to run on Python 3 due to dependancy on sleekxmpp
pip install pycrypto
pip install sleekxmpp