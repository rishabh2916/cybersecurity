# HTTP in detail - How the web works

HTTP(HyperText Transfer Protocol) is the protocol that specific how a web browser and a web server communicate. Your web browser requests content from the Tryhackme web server using the HTTP protocol.

![flag capture img](./assets/http-flag-img.png)

## Requests and Response

### URL (uniform resource locator)

A URL is predominantly an instruction on how to access a resource on the internet.

![How URL Look like](./assets/domain%20structure.png)

- **Scheme:** This instructs on what protocol to use for accessing the resource such as HTTP, HTTPS, FTP (File Transfer Protocol).

- **User:** Some services require authentication to log in, you can put a username and password into the URL to log in.

- **Host:** The domain name or IP address of the server you wish to access.

- **Port:** The Port that you are going to connect to, usually 80 for HTTP and 443 for HTTPS, but this can be hosted on any port between 1 - 65535.

- **Path:** The file name or location of the resource you are trying to access.

- **Query String:** Extra bits of information that can be sent to the requested path. For example, /blog?id=1 would tell the blog path that you wish to receive the blog article with the id of 1.

- **Fragment:** This is a reference to a location on the actual page requested. This is commonly used for pages with long content and can have a certain part of the page directly linked to it, so it is viewable to the user as soon as they access the page.

### Making a Request

It's possible to make a request to a web server with just one line GET / HTTP/1.1
![Making a request of URL](./assets/url%20request.png)

But for a much richer web experience, you’ll need to send other data as well. This other data is sent in what is called headers, where headers contain extra information to give to the web server you’re communicating with, but we’ll go more into this in the Header task.

1. **Example Request**

GET / HTTP/1.1

**Host**: tryhackme.com
**User-Agent**: Mozilla/5.0 Firefox/87.0
**Referer**: https: //tryhackme.com/

To breakdown each line of this request:

**Line 1:** This request is sending the GET method ( more on this in the HTTP Methods task ), request the home page with / and telling the web server we are using HTTP protocol version 1.1.

**Line 2:** We tell the web server we want the website tryhackme.com

**Line 3:** We tell the web server we are using the Firefox version 87 Browser

**Line 4:** We are telling the web server that the web page that referred us to this one is https:// tryhackme.com

Line 5: HTTP requests always end with a blank line to inform the web server that the request has finished.

## HTTP Methods

**GET Request:** This is used for getting information from a web server.

**POST Request:** This is used for submitting data to the web server and potentially creating new records

**PUT Request:** This is used for submitting data to a web server to update information

**DELETE Request:** This is used for deleting information/records from a web server.

| Range / Code | Category / Status | Description |
| :--- | :--- | :--- |
| **100–199** | **Informational Response** | These are sent to tell the client the first part of their request has been accepted and they should continue sending the rest of their request. These codes are no longer very common. |
| **200–299** | **Success** | This range of status codes is used to tell the client their request was successful. |
| * 200 | OK | The request was completed successfully. |
| * 201 | Created | A resource has been created (for example a new user or new blog post). |
| **300–399** | **Redirection** | These are used to redirect the client's request to another resource. This can be either to a different webpage or a different website altogether. |
| * 301 | Moved Permanently | This redirects the client's browser to a new webpage or tells search engines that the page has moved somewhere else and to look there instead. |
| * 302 | Found | Similar to the above permanent redirect, but as the name suggests, this is only a temporary change and it may change again in the near future. |
| **400–499** | **Client Errors** | Used to inform the client that there was an error with their request. |
| * 400 | Bad Request | This tells the browser that something was either wrong or missing in their request. This could sometimes be used if the web server resource that is being requested expected a certain parameter that the client didn't send. |
| * 401 | Not Authorised | You are not currently allowed to view this resource until you have authorised with the web application, most commonly with a username and password. |
| * 403 | Forbidden | You do not have permission to view this resource whether you are logged in or not. |
| * 404 | Page Not Found | The page/resource you requested does not exist. |
| * 405 | Method Not Allowed | The resource does not allow this method request, for example, you send a GET request to the resource /create-account when it was expecting a POST request instead. |
| **500–599** | **Server Errors** | This is reserved for errors happening on the server-side and usually indicate quite a major problem with the server handling the request. |
| * 500 | Internal Service Error | The server has encountered some kind of error with your request that it doesn't know how to handle properly. |
| * 503 | Service Unavailable | This server cannot handle your request as it's either overloaded or down for maintenance. |
