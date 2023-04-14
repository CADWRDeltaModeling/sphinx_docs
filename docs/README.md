The *docs* folder is where Sphinx will produce the *index.html* file (the main web page HTML file) and the supporting files in *html* and *doctrees*.

For readthedocs, sphinx puts the index.html file within the 'html' folder. So the index.html file found here is just a link to the correct html/index.html file using:

<meta http-equiv="refresh" content="0; url=./html/index.html" />
