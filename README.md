# iseCTF-2019

Freebie
>This question is to get used to the flag format
>
>Flag : iseCTF{e4sy_doe5_It}

Weird website
>Change the user agent on the browser to ise
>
>Flag : iseCTF{bRoW5E_DrOws3}

Mad Bots
>Refers to the robots.txt file on the server
>Navigate to url/robots.txt and then to the disallowed page
>
>Flag :  iseCTF{The_b07s_Are_COM1ng}

Dah...dit...  
>Write a script to change all the dahs to "-" and the dits to "."
>Translate the resulting morse code
>
>Flag : iseCTF{secretive}

Reactors 
>The page is vulnerable to SQL injection
>Type ' or 1=1# to find a table called not_here
>Navigate to the table not_here using the union command by typing
>' or 1=1 union select * from not_here#
>
>Flag : iseCTF{h@cK3D_D@t4BAS3}

Wicked postman 
>It is clear that a post request is to be sent to the server with the parameter flag="real"
>Use cURL : curl -d "flag=real" -X POST https://isctf.000webhostapp.com/Wicked_Postman.php
>
>Flag : iseCTF{Pos7_R34L1ty}

Sly Kitten 
>Extract the jpeg file to get a folder with meh.txt
>meh.txt has a png header and is a png image saved as a text file
>Convert meh.txt to a .png
>Scan the qr code to get the flag.
>
>Flag : iseCTF{st3g0_15_Co0l}

A train journey 
>The question refers to both base64 encoding and rail cipher with a step value of 4
>convert the base 64 into regular text and decode the rail cipher
>
>Flag : iseCTF{MURDERONTHEORIENTEXPRESS}

Lost in the server 
>Apply an enumeration operation on the website
>A site called url/Emu exists with the flag
>
>Flag : iseCTF{pE7_d3teCT1V3}

1s and 0s 
>Run strings on the picture to get a key called not_here
>Convert the key to hex and XOR with the given data
>Convert the final hex into a png image to get a qr code that contains the flag
>
>Flag : iseCTF{Y0ur_Br3atht4kinG}

Sweet pupper
>Run strings on the image to get the flag
>
>Flag : iseCTF{pUppER_1OV3}

Password protected
>View the source of the page to get a hash
>crack the hash to get a password called "sleepy"
>
>Flag : iseCTF{md5_H4Sh_FunC7iOn}

Pissed off
>Run a script on the file to get brainfuck characters out
>Decode the brainfuck to get the first part of the flag
>The second part of the flag is encoded in base64 after the "hahanotyet!" string in the file
>
>Flag : iseCTF{PI$53D_0fF_coMPuter5}


