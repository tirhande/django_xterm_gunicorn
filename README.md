# django_xterm_gunicorn

The xterm connection is made through two modules.

1. django_xterm
   - Django Admin Web
   - django_xterm.conf -- nginx.conf file
   - django_xterm.service -- gunicorn service file (CentOS, Rocky)



2. django_socket
   - Internal socket module for django_xterm connection
   - django_socket.service -- gunicorn service file (CentOS, Rocky)

django_xterm and django_socket are connected by websocket to implement real-time connection.


# Credit
This repository is a copy of

[MahmoudAlyy/django-xtermjs](https://github.com/MahmoudAlyy/django-xtermjs)

[cs01/pyxterms](https://github.com/cs01/pyxtermjs)

xterm with gunicorn service.


# Installation

- After login, click the "View Site" button at the top right to access xterm
