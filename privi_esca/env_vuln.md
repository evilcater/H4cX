# ENV VULN

- 1

We can copy the executable "cat" to to tmp/ as "ls"
--> 

    "cp /bin/cat /tmp/ls"
Next export the env var to /tmp
-->

     export PATH=/tmp
and we can execute ls as cat !
