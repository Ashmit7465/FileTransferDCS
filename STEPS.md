# RPC Based server for file operations

## Server setup 
Run the following on server folder to start the server setup . Enter into server directory and run
```
python3 server.py
```
It will listen to the port of `8000` by default.

## Client setup 
Run the following to run client based problems from client side. Enter into client directory and run

```
python3 client.py
```

# FILE OPERATIONS

## Upload
To upload a file use 

```
python3 client.py --upload <filename>
```
eg:
```
python3 client.py --upload client_1.txt
```

## Delete
To delete a file use 

```
python3 client.py --delete <filename>
```
eg:
```
python3 client.py --delete server_22.txt
```

## Download
To download a file from server side, we can use

```
python3 client.py --download <filename>
```
eg:
```
python3 client.py --download server_2s.txt
```

## Rename
To Rename a file on server side, we can use

```
python3 client.py --rename <actualFileName> --renameTo <changeToFileName>
```
eg:
```
python3 client.py --rename server_3.txt --renameTo server_4.txt
```

## Add
To add two numbers
```
python3 client.py --add 5,3
```

## Sort Array 
To sort the array , pass the array as argument 

```
python3 client.py --sort 50,3,8,1,76,34
```


