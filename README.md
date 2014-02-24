remoteDoc-2014-2-13
===================
曾经用rm 弄丢了的书，有些文档丢了找不回了
Beginning Ubuntu Linux_6th Edition.pdf

hackers.pdf
NetworkSimulationExperimentsManual.pdf
opnet ---Network Simulation Experiments Manual.pdf
The Official Ubuntu Book 7th Edition_Prentice Hall  2012.pdf

//It's obviously a fuzzier search but handy if you're not sure which package you're looking for.
dpkg -l | grep -E '^ii' | grep firefox


//To check whether a package is install also
dpkg -l | grep chromium-browser
