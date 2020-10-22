# OS_Assignment4

i used the code from date_server and only edited the client helper method
run the server: ./server 127.0.0.1 5001
than open up firefox and type in 127.0.0.1:5001

- i put the index file into the directory, the server is hardcoded to just open it, it reads the file and puts all the data into a char[] then I append it after the http response header.
- writes all the data of the body (not the header) to the client (firefox)

## To Do
- read what file the client wants( idk if we are doing only index.html or if he would like to open other files).
- check if file exists and if permissions are set
- giving me problems when I use telnet!!! need to make it work with using GET command
- It just prints the html line by line like a txt file but it doesn't actualy make the page look like an html page
- maybe we have to do multiple reads and writes. like using a while loop, just need to send the header first pretty sure
- other small stuff 

VERY  helpful link
https://medium.com/from-the-scratch/http-server-what-do-you-need-to-know-to-build-a-simple-http-server-from-scratch-d1ef8945e4fa
