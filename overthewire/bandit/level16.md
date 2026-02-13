# Username
bandit16

# Password
kSkvUpMQ7lBYyCM4GBPvCvT1BfWRy0Dx

# Method of solve
scan ports and connect to correct SSL service

nmap -p 31000-32000 localhost
openssl s_client -connect localhost:31790
