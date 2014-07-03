#Addition using JavaScript Transformer

This example shows how to parse an incoming JSON message and process it using the JavaScript transformer.

###Assumption

This document describes the details of the example within the context of Anypoint™ Studio, Mule ESB’s graphical user interface (GUI). This document assumes that you are familiar with Mule ESB and the [Anypoint Studio interface](http://www.mulesoft.org/documentation/display/current/Anypoint+Studio+Essentials).

### Example Use Case

In this example, we send a JSON message containing two munbers to an HTTP endpoint. This Byte Array of data is transformed to a String. The JavaScript transformer then processes the data and adds up the numbers. The sum is then returned to the HTTP endpoint.

### Set up and Run the Example


1  Open this example project in studio and run it

2  Use Postman, curl or REST console to make a POST request using JSON. The message body should contain the following data:

    {
    "a": 3, "b": 4
    }

3 If the project is running successfully you should get the following message onyour studio console.

    INFO  2014-07-02 16:44:34,235 [[javascript-calculator].connector.http.mule.default.receiver.03] org.mule.api.processor.LoggerMessageProcessor: Sum is: 7.0
    
    
###Go Further

* Read more about Scripting in the Anypoint platform [here](http://www.mulesoft.org/documentation/display/33X/Scripting+Example)

* Read more about the JavaScript Component [here](http://www.mulesoft.org/documentation/display/current/JavaScript+Component+Reference)
