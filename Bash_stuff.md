## reverse DNS brute force
for ip in $(seq 1 255);do host -a 10.11.1.$ip [dns server];done | grep  "3600"

## reverse ip address for DNS lookup 
sed -r 's/^([0-9]{1,3})\.([0-9]{1,3})\.([0-9]{1,3})\.([0-9]{1,3})/\4.\3.\2.\1/' [file name]

##install a deb file
sudo dpkg -i /path/to/deb/file
sudo apt-get install -f

