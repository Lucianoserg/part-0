# part-0

0.4 Nueva nota:

browser->server: HTTP POST https://studies.cs.helsinki.fi/exampleapp/new_note
browser->server: HTTP GET https://studies.cs.helsinki.fi/exampleapp/notes
server-->browser: HTML-code
browser->server: HTTP GET https://studies.cs.helsinki.fi/exampleapp/main.css
server-->browser: main.css
browser->server: HTTP GET https://studies.cs.helsinki.fi/exampleapp/main.js
server-->browser: main.js


0.5: Aplicación de una sola página

browser->server: HTTP GET https://studies.cs.helsinki.fi/exampleapp/spa
server-->browser: HTML-code
browser->server: HTTP GET https://studies.cs.helsinki.fi/exampleapp/main.css
server-->browser: main.css
browser->server: HTTP GET https://studies.cs.helsinki.fi/exampleapp/main.js
server-->browser: main.js

0.6: Nueva nota

browser->server: HTTP POST https://studies.cs.helsinki.fi/exampleapp/new_note_spa
como la pagina no recarga el browser no vuelve a solicitar los demas archivos de css y js