Xcode-Cleanup-Script
====================
  
My tiny Macbook Air was hungry for disk space and there were more than 18GB of unused files for xcode caching and application supports. So I wrote a shell script to cleanup those files. For files to be deleted and their usage, check this blog (http://blog.favo.org/post/31649090293/xcode-5-places-to-save-some-disk-space).  
  
Files to be removed  
~/Library/Developer/Xcode/Archives/*  
~/Library/Developer/Xcode/DerivedData/*  
~/Library/Developer/Xcode/iOS DeviceSupport/*  
~/Library/Application Support/iPhone Simulator/?/Applications  
~/Library/Application Support/iPhone Simulator/?/tmp/ghostlyIcons.*  
~/Library/Application Support/iPhone Simulator/?/tmp/gridImages.*  
~/Library/Application Support/iPhone Simulator/?/tmp/iconImages.*  
~/Library/Application Support/iPhone Simulator/?/tmp/iconLabels_gray.*  
  
? : Version of iOS Simulator  
  
Usage  
  
./xcode_cleanup.sh
