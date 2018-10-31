_LineageOS 14.1 for LG G Pad X2 8.0 Plus_
---------------------------

the local manifests:

	$ repo init -u git://github.com/LineageOS/android.git -b cm-14.1
	$ git clone https://github.com/LG-MSM8940/manifest -b v530_cm-14.1 .repo/local_manifests

Then sync up with this command:

	$ repo sync --force-sync
	
You can make the 4 higher depending on how fast your internet connection is. 
