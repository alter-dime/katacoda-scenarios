* cat sample.csv | awk -F ';' '{print $4}' > lastname.txt
* cat lastname.txt | sed -e 's/Smith/Jackson/g'
