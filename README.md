# Welcome to ASP.NET 5 on Heroku


## This application consists of:

*   Sample pages using ASP.NET MVC 6
*   [Gulp](http://go.microsoft.com/fwlink/?LinkId=518007) and [Bower](http://go.microsoft.com/fwlink/?LinkId=518004) for managing client-side libraries
*   Theming using [Bootstrap](http://go.microsoft.com/fwlink/?LinkID=398939)

## How to

,,,,bash
git clone https://github.com/sfielder/herokudotnet
git init
git add .
git commit -m "deploy .net to heroku"
heroku create yourappname
heroku buildpacks:set https://github.com/jincod/dotnet-buildpack
git push heroku master
heroku open

,,,,
