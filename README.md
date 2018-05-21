# a web-server implemented in C
It is a project for an OS course in NCKU

Use a lot of code from https://github.com/shenfeng/tiny-web-server


# Developer guide:
1. run `$ make` and you will see a file `tiny` generated, 
2. run `$ ./tiny` and you will see a port opening at `8080` like the following:
```
$ ./tiny
listen on port 8080, fd is 3
child pid is 10181
child pid is 10182
child pid is 10183
child pid is 10184
child pid is 10185
child pid is 10186
child pid is 10187
child pid is 10188
child pid is 10189
child pid is 10190
```
3. run  `$ telnet localhost 8080` **in the other terminal**, and you will see that it connect to localhost if port 8080 is not ocupied.

4. now you can use HTTP request to get HTTP response, if you don't know how to write a HTTP request, you can just open a browser and connect to it with URL like `localhost:8080`
