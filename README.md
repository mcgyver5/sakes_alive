# sakes_alive

I need a script that loops over a  list of domains and / or URLs and reports if a web server is alive there.

INPUT:
A list of domains or IP addresses or URLs and, optionally ports, delimited

PROCESS:
do a http request to the provided address and record the response code.  if a response code is recieved, do a site: google search to collect any publicly known URLs

OUTPUT:
a list of live websites suitable for further research
