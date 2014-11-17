Description
-------------

- FIGWAY is an opensource tool to work with FIWARE Orion ContextBroker and/or FIWARE IDAS.2.6 (also known as SBC2.6).  

- The newest version is all under the "python/" folder. It is written in python and it has been tested in RaspberryPI, MacbookPro
 with OSX 10.9.3. It should work fine in any linux or any other system with python2.7 installed. 

-  The "c++/" folder holds the previous version written in C++ and working only in RaspberryPI platform. You will find in
 that folder specific instrcutions while the rest of this file refers to the newest one at "python/".

- Prior to use this software, you need to configure it at "python/config.ini".
 Note that to obtain the "token" within "" configuration you need to have an account at http://www.fi-ware.org/lab/ and then
 execute the script "python/get_token.py".

- Current available folders:
python/ContextBroker/  -> specific tools to talk to a ContextBroker. We are working on a specific README.md for this folder.
                           Meanwhile, execute the commands with no arguments for help.
python/SensorsUL20/    -> specific tools to talk to IDAS2.6 and simulate virtual sensors (using Ultralight 2.0).
                           There is an specific README.md file in this directory.



Credits
------------
- Developed by Carlos Ralli Ucendo (@carlosralli). Nov 2014.
- Thanks to Rafael Baños Lopez for his great support for his support and lots of testing/debugging efforts!
