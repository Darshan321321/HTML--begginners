# HTML--begginners
Studing for 3-5 hours a day
HTML - markup language : 2.5 week
CSS - stuling language : 2.5 week
JavaScript - Programming language : 6 weeks
first three months of above topics
React js: its not a framework its a library of javascript and most popular :2 months
Angular js and vue : its a framework
Help us build applications faster by framework
Version control system - git : 2 week

# How--the--web--works
http://www.codewithmosh.com is an URL
URL : Uniform Resource Location is basically a way to locate the web resources on the internet
Resources can be of any form
1.Web pages(HTML DOCUMENTS)
2.Images 
3.Video files 
4.Fonts
When we type any Url on a browser , What happens now
Browser                     -- client : Who requests the service
Computers that host the url -- server : Provides the service
Browser Sends the message to the sever : Hey give me the home page of the website "http://www.codewithmosh.com"
This message is formatted based on the protocol called http: Hyper Text Transfer Protocol
Http is a language that client and servers use to talk with each other.
Https : Http with encrypted messages sent to each other for the protection 
Example :
1.Client sends this message:
# get home page of host website using http protocol in English -us language --http request
GET /index.html HTTP/1.1 
Host: www.codewithmosh.com
Accept-Language : en-us
2.Server receives the message:

HTTP/1.1 200 OK # version status code OK
Date: 1 Jan 2021 09:00 # date and time of response
Content-Type : text/html # type of the content the sever is sending back to client

<!DOCTYPE HTML> #html document
<html>
  ...
<html>  

3.The browser reads this html document and constructs what we call a DOM(DOCUMENT OBJECT MODEL)
  its a model that represents the object and elements in out html document 
  Elements : all the bulding blocks of our page like paragraphs of text images, links etc
4.When the browser is reading the html document it may discover the references to other resources in the document,
  Each resources has its own URL, so the browser sends the many of the http requests to the server to fetch that resource , Many of the http requests are set in parallel, so we can see the page asap.
5.Once the browser has all the necessary resources it will render the html docmunent.
  Render the html document means displaying it
  
 #Inspecting HTTP requests and responses
  1.inspect any of the web page 
  2.Go to the network section 
  3.Do the analysis which developers do

