About
===========


Check the version:

	python  -V    

Download:

	wget http://python.org/ftp/python/2.7.3/Python-2.7.3.tar.bz2  

Extract:

	tar -jxvf Python-2.7.3.tar.bz2  
	cd Python-2.7.3  

Compile and install:

	./configure  
	make all          
	make install  
	make clean  
	make distclean  
	/usr/local/bin/python2.7 -V  

Build soft link:

	mv /usr/bin/python /usr/bin/python2.6.6  
	ln -s /usr/local/bin/python2.7 /usr/bin/python 

Check version again:

	python -V  

Change configure:

	vi /usr/bin/yum  

