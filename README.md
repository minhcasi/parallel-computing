parallel-computing
==================

The given class(or set of classes) helps to run PHP scripts or their parts into separate processes, which can be cooperated through the given classes. Process means execution of every instance of the script.

For example: there is a script, generating thousands of requests to external web-service, then receiving a data and store into a database. Web service request process is time consuming, so all the requests should run in parallel.
To parallelize the script means to run several copies of the script, which executes a request to the part of the web-service only. 
