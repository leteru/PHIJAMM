# PHIJAMM
ABOUT:

PHIshing JAMMing tool v 1.0 :
This tool is pretended to be used as an anti-phishing attack. It distrube the target by sending mass-fake login combos .

The first version of this tool is a graphic user tool based on a background console tool , thus one can use console or GUI to lunch the attack .
The console tool is programmed with Perl ans compiled as win32 application console.
The GUI is programmed with AutoIt and used to handle the console application .





SYNOPSIS:

phijamm   -u [url]   -ux1   -src [file]   -req [file]   -emaillst [file]   -passlst[file]   -sleep [value]   -ux2   -ur   -max [value]

-u            The URL of the phishing page 

-ux1          Use proxy to first connect to the phishing page

-src          HTML Source-Code of the phishing page

-req          POST Request  file

-emaillst     The fake email list

-passlst      The fake password list

-sleep        Time between each request

-ux2          Use a different proxy for any request

-ur           Use referer

-max          The max number of requests
