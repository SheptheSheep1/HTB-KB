---
layout: default
title: Network Traffic Analysis (NTA)
nav_order: 2
---
# Tcpdump Fundamentals
## Utilizing the output shown in question-1.png, who is the server in this communication? (IP Address)
174.143.213.184
## Were absolute or relative sequence numbers used during the capture? (see question-1.zip to answer)
relative
## If I wish to start a capture without hostname resolution, verbose output, showing contents in ASCII and hex, and grab the first 100 packets; what are the switches used? please answer in the order the switches are asked for in the question.
-nvXc 100
## Given the capture file at /tmp/capture.pcap, what tcpdump command will enable you to read from the capture and show the output contents in Hex and ASCII? (Please use best practices when using switches)
sudo tcpdump -Xr /tmp/capture.pcap
## What TCPDump switch will increase the verbosity of our output? ( Include the - with the proper switch )
-v
## What built in terminal help reference can tell us more about TCPDump?
man
## What TCPDump switch will let me write my output to a file?
-vv
