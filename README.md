# Eggly - a bookmark manager built with AngularJS


A project to develop a bookmark manager app, following an [egghead] course.

![](public/IMG_1456.JPG)

## Learning Objectives
- To improve my AngularJS skills


## How to run it
```sh
$  git clone git@github.com:StephanMusgrave/Eggly.git
$  cd eggly
$  python -m SimpleHTTPServer
  =>  http://localhost:8000/index.html#/

```

Heroku
----
Click here to open the web page on Heroku: [App on Heroku]

## Technologies used

|Technology                 |Used for                        |
|---------------------------|--------------------------------|
|Javascript                 |Programming language            |
|AngularJS                  |a web application framework for creating one-page web applications that only require HTML, CSS, and JavaScript on the client side |
|ui-router                  |State-based routing for AngularJS, an alternative to AngularJS's default routing module |
|Heroku                     |Deployment: [App on Heroku]     |
|HTML5                      |Web Pages                       |
|CSS3                       |Styling                         |
|Glypicons                  |for styling links and buttons   |

## Developed by

[Steve Musgrave]

## Further work to do

[Steve Musgrave]:https://github.com/StephanMusgrave
[App on Heroku]:https://eggly-musgrave.herokuapp.com/
[egghead]:https://egghead.io/


#Local Server:
If you need a quick web server running and you don't want to mess with setting up apache or something similar, then Python can help. Python comes with a simple built in HTTP server. With the help of this little HTTP server you can turn any directory in your system into your web server directory. The only thing you need to have installed is Python.

Practically speaking this is very useful to share files inside your local network. Implementing this tiny but hugely useful HTTP server is very simple, its just a single line command.

Assume that I would like to share the directory /home/hisam and my IP address is 192.168.1.2

Open up a terminal and type:

$ cd /home/somedir
$ python -m SimpleHTTPServer
That's it! Now your http server will start in port 8000. You will get the message:

Serving HTTP on 0.0.0.0 port 8000 ...
Now open a browser and type the following address:

http://192.168.1.2:8000
You can also access it via:

http://127.0.0.1:8000
If the directory has a file named index.html, that file will be served as the initial file. If there is no index.html, then the files in the directory will be listed.

