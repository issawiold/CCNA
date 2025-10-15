# CCNA Telnet Command Guide

\> EN  
\# CONF T  
fig\# INT G0/0  
if\# IP ADD ###.###.#(ip address) ##.### ###.###.#(subnetmask) ##.###  
if\# EXIT  
fig\# HOSTNAME R1  
fig\# LINE VTY 0 15  
line\# LOGIN LOCAL  
line\# TRANSPORT INPUT TELNET  
