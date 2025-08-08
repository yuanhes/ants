# ants
A tower defense game project from the UCB CS61A course.

# deploy command
```
gunicorn "gui:create_app()" -k eventlet -w 1 -b 0.0.0.0:5080
```
