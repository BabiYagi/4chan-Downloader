# 4chan-Downloader
4chan Media Downloader

I made this script so you nice and easily can download all media files from any thread on 4chan.org.

To run the script, you need to have Python 3.7 plus the following modules installed:
	
	bs4
	argparse
	urllib
	os
	sys
	re
	datetime
	time
	hurry.filesize
	shutil
  
To save the files in a folder created by the script, type in the following command:

	python downloader.py -u [url]

To save the files in a folder created by the script, and save that folder in a specific folder of your choosing, type in the following:

	python downloader.py -u [url] -d [absoulute path to folder]

To automatically overwrite any folder with the same name as the folder the script is creating, type in:
	
	python downloader.py -u [url] -d [absoulute path to folder] -o
	
To save the files of multiple threads at once in a folder created by the script, type in:

	python downloader.py -l "[url1] [url2] [url3] ..."
	
To save the files of multiple threads at once (takes an unlimited amount of threads) in a folder created by the script, and save that folder in a specific folder of your choosing, type in:

	python downloader.py -l "[url1] [url2] [url3] ..." -d [absoulute path to folder]
	
To automatically overwrite any folders with the same name as the folders the script are creating, type in:

	python downloader.py -l "[url1] [url2] [url3] ..." -d [absoulute path to folder] -o

For help, type in:

	python3 downloader.py -h
