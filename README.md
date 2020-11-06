# Tryhackme_ctf_collection_vol1
useful brain storming stegnography , cryptography have fun!!


### tools used for solving:exiftool,steghide,binwalk,vim lookup,strings ,lots of online qr,base16,hex,xor,caeser cipher,rot13,hex to ascii,vigenere cipher decoder ,wireshark for analysing the packet

## these are the flags finded during solving:
#ctf collection vol 1

task 1 no flag

task 2
VEhNe2p1NTdfZDNjMGQzXzdoM19iNDUzfQ==
hint:base64
THM{ju57_d3c0d3_7h3_b453}

task 3
find flag in the given image
THM{3x1f_0r_3x17}

task 4
THM{500n3r_0r_l473r_17_15_0ur_7urn}

task 5
THM{wh173_fl46} (just highlighting the text)

task 6 
qr code
THM{qr_m4k3_l1f3_345y}

task 7
THM{345y_f1nd_345y_60}

task 8 base58 deocoder
THM{17_h45_l3553r_l3773r5}

task 9 caeser cipher / rot 13
THM{hail_the_caesar}


task 10
 THM{4lw4y5_ch3ck_7h3_c0m3mn7} 



task 11
xxd --plain spoil.png > myhexdump.txt



task 12 reddit
THM{50c14l_4cc0un7_15_p4r7_0f_051n7}

task 13 crack the strings
THM{3xclu51v3_0r}


task 14
THM{y0u_w4lk_m3_0u7}



task 15
wget http://www.caesum.com/handbook/Stegsolve.jar -O stegsolve.jar
chmod +x stegsovle.jar
THM{7h3r3_15_hOp3_1n_7h3_d4rkn355}

task 16
qr code:
THM{SOUNDINGQR}

task 17 wayback machine
THM{ch3ck_th3_h4ckb4ck} 


task 18 done 


task 19 crack the vigenere cipher
TRYHACKME{YOU_FOUND_THE_KEY}

task 20 decode the following
THM{17_ju57_4n_0rd1n4ry_b4535}


task 21




Frame 1827: 455 bytes on wire (3640 bits), 455 bytes captured (3640 bits) on interface eth0, id 0
Ethernet II, Src: VMware_fb:30:11 (00:0c:29:fb:30:11), Dst: VMware_2d:ec:c9 (00:0c:29:2d:ec:c9)
Internet Protocol Version 4, Src: 192.168.247.140, Dst: 192.168.247.130
Transmission Control Protocol, Src Port: 80, Dst Port: 36654, Seq: 1, Ack: 441, Len: 389
Hypertext Transfer Protocol
    HTTP/1.1 200 OK\r\n
    Date: Fri, 03 Jan 2020 04:43:14 GMT\r\n
    Server: Apache/2.2.22 (Ubuntu)\r\n
    Last-Modified: Fri, 03 Jan 2020 04:42:12 GMT\r\n
    ETag: "e1bb7-20-59b34eee33e0c"\r\n
    Accept-Ranges: bytes\r\n
    Vary: Accept-Encoding\r\n
    Content-Encoding: gzip\r\n
    Content-Length: 52\r\n
    Keep-Alive: timeout=5, max=100\r\n
    Connection: Keep-Alive\r\n
    Content-Type: text/plain\r\n
    \r\n
    [HTTP response 1/1]
    [Time since request: 0.001753335 seconds]
    [Request in frame: 1825]
    [Request URI: http://192.168.247.140/flag.txt]
    Content-encoded entity body (gzip): 52 bytes -> 32 bytes
    File Data: 32 bytes
Line-based text data: text/plain (3 lines)
    THM{d0_n07_574lk_m3}\n
    \n
    Found me!\n









task 13 brainfuck
THM{0h_my_h34d}
