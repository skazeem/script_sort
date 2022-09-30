# script_sort
#!/bin/bash
#sort -t: -k3,3 /etc/passwd | grep $1 | awk -F: '{ print $3,$4,$6,$7,$1 }' > /tmp/test2
cat /tmp/test2 | grep $1
