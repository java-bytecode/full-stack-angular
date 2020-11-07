# Java Full Stack 

## Web Services

HTML is not really a format for application to application interaction.

A web service enables communication among various applications by using open standards such as HTML, XML, WSDL, and SOAP.

### 3 Keys

1. Designed for machine-to-machine (or application-to-application) interaction.

2. Should be interoperable - Not platform dependent.

3. Should allow communication over the network. 

### Terms

* **Request**: Input to a web service.

* **Response**: Output from a web service.

In order for a web service to be platform independent, the **request** and **response** formats should be platform independent.

### Formats or Message Exchange Formart

* **XML**: Extensible Markup Language

* **JSON**: Javascript Object Notation
    - How Javascript represents its objects.

## Service Definition

* Q) How does the application know what request to send? Where to send it? What is the format of the response?

Service Definition defines -

* Request/Response Format

* Request Structure

* Response Structure

* Endpoint

**Service Definition** - It is the contract between service provider (server) and service consumer (client).

**Service Provider**

_Server_

**SP** is the one which hosts the web service.

**Service Consumer**

_Client_

**SC** is the one which consumes the web service.

### Transport

How the service should be called?

 - HTTP (Over the web)
 - MQ (Communication over Queue)

### REST

**Representational State Transfer**

It is completely built on HTTP. 

HTTP contains -

* HTTP Headers
* Content
* HTTP Request Methods
* HTTP Response Status Codes

#### HTTP Request Methods

* GET
* POST
* PUT
* DELETE
* PATCH

#### HTTP Response Status Codes

200 OK

404 NOT FOUND

etc.

**Resources**

Everything is a resource in REST. It is anything that you want to expose to the outside world through your application.

`/users/` - users are a resource.

`/users/Cyber` - Cyber is a resource.

`/users/todos` - todos is a resource.

`/users/Cyber/todos/1` - the first todo resource of the user "Cyber".

**No Service Definition**

* WADL - One of the formats in which you can specify your RESTful Web Services.

* Swagger

