# Mac-Vendor
Lookup vendor of MAC address

You can also provide a text file containing various mac addresses (one per line).  
This script download a little text file containing all MAC vendors, and search based on this file.  
If you have problem in finding some vendor, you can use the param "-r" to re-download the file again.  
  
Supports 4 MAC formats:  
aabbccddeeff, aa:bb:cc:dd:ee:ff, aa-bb-cc-dd-ee-ff or aabb.ccdd.eeff

UPDATE 25/03/2018!  
Now, it can be used as library.  
Example:  
import macvendor  
mac_formatted, vendor = macvendor.Vendor(mac)  

![Mac Vendor Lookup](https://raw.githubusercontent.com/victor-oliveira1/Mac-Vendor/master/mac_vendor.png)

victor.oliveira@gmx.com
