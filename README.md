# Index_Test_Addon
A simple addon to test the functionality of the index_server

run  make to compile

create the folder /boot/home/config/non-packaged/add-ons/index_server
mkdir /boot/home/config/non-packaged/add-ons/index_server
cd objects.x86-gcc2-debug/
 ln -srf TestAnalyser /boot/home/config/non-packaged/add-ons/index_server/

Then Pls run index_server from terminal

and watch it work :-D
It will generate a folder  ./IndexServer in your root 
Also the Log will be there.
Since we cant specifiy folders / Files not to watch.. it
will recurisvly "alert the Log file" since it will be change
and then it will alert to the TestAddon wich will log it into
the log wich will "alert the Log file" So dont expect the index_server 
ever to be silent
