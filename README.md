<a href="https://www.ongoingwarehouse.com">![Logo](https://www.ongoingwarehouse.com/images/logotype.png)</a>
# Ongoing Warehouse Automation API example requests
[Ongoing WMS](https://www.ongoingwarehouse.com/) is a Warehouse Management System (WMS).

We provide several [Application Programming Interfaces (APIs)](https://developer.ongoingwarehouse.com/). One of them is called [the Automation API](https://developer.ongoingwarehouse.com/Automation-API). This API allows an external system to perform certain internal warehouse operations, like moving goods from one location to another.

In this repository, we provide a [Postman](https://www.postman.com/) collection containing some example requests for the automation API. Postman is a program which can make API requests. You can use it to test out APIs. Note that the collection uses [Postman variables](https://learning.postman.com/docs/sending-requests/managing-environments/), which you will have to modify to suit your particular case. You will also have to fill in the username and password for your API user.

We also provide a WSDL file for the API. This is a machine-readable specification of the API, which allows you to automatically generate client code for your own programming language. You can find the WSDL file by appending `?WSDL` to the endpoint URL:

```https://api.ongoingsystems.se/apidemo/Automation.asmx?WSDL```