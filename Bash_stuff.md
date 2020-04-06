## reverse ip address for DNS lookup 
sed -r 's/^([0-9]{1,3})\.([0-9]{1,3})\.([0-9]{1,3})\.([0-9]{1,3})/\4.\3.\2.\1/' [file name]
