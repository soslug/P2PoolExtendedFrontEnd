P2PoolExtendFrontEnd
====================

Extended front end web interface for p2pool

How install
====================
Put all these files on web-static folder of your p2pool node installation

Disclaimer
==========

With absolutely no disrespect intended to either "Hardcpp" or "Head" I have made some changes for my own needs rather than to steal any credit I have no developing skill myself but have contributed in a small way or rather our club has to the development of the "Head" repository in particular.

I have made changes to the following files:-

README.md - This file
index.html - Modified contact to point to http://soslug.org my website to encourage further development and provide a point of contact. Also added an attribute to Bitcoin address link to open a new blockchain page tab and leave original status page opened.

graphs.html - Has also been changed so the "Miners" block on the "grahps.html" page not only shows the addresses of the attached miners but provides a clickable link to the blockchain. Again I cannot take credit for the work done on this page it was beyond me but my team did, many thanks for there support and Andrew Knight and Andrew Melder in particular both "Southend on Sea Linux User Group" along with myself.

Notes
=====

"P2PoolExtendedFrontEnd" is the web interface of choice if you plan to use any of these extended web interface files you must first install and use the p2pool "Hardcpp" files or one of its branch code alternatives. First install p2pool onto your server delete the web-static folder completely then either download to the server and into a folder called "web-static" the repository P2PoolExtendedFrontEnd files several ways you can do this I prefer to maintain the original cloned directory albeit a different path location and link directory to "web-static" in "p2pool" the original directory.

You need if you intend to these files to remember to add the port address after your chosen domain name in my case http://p2pool.soslug.org:9332 it does work much better that way.
