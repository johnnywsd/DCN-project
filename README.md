Build
-------------

Run this command:
```
$ ant
```

It will generate Server.jar and Client.jar in ./bin/jar folder
It also copy a sample Mjpeg file to that folder (movie.Mjpeg)


Run
------------

Go to folder ./bin/jar

1. Start the server:
```
java -jar Server.jar 2222
```

2. Start the client:

```
java -jar Client.jar localhost 2222 movie.Mjpeg
```
