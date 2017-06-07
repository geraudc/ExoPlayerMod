# Answers #

## 1. What are the limitations of your implementation? ##

Limitations are :  
 - Intrusive implementation
 - Need an active console

## 2. What could go wrong if your solution is put in production into a customer’s app ? ##

Logging of HTTPS requests must not be used. This has negatives impacts on security.

## What could you do to improve the current implementation? ##

Use this :  
https://github.com/square/okhttp/tree/master/okhttp-logging-interceptor

Or a non intrusive solution with Wireshark (tested with http but not https).


