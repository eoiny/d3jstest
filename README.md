d3jstest
========
@ Eoiny please follow these instructions

- clone the repo
- run npm install && bower install on it
- grunt serve
- you should see a pie chart
- grunt build
- you should get a dist folder
- cd to dist folder
- run python -m SimpleHTTPServer (if you have a mac)
- go to localhost:8000
- yo should see the pie chart

** the problem you are having is not with bower or d3 or grunt its with your directive and how you are creating your chart. Take a look
at my directive "linechart"
