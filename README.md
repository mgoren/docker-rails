# test docker rails app development with binding.pry

**added these two lines to web section of docker-compose.yaml**
```
- stdin_open: true
- tty: true
```

**to be able to access command line in binding.pry:**
`docker attach [container_id]`

**test this example:**
`localhost:3000/posts`
(should pop you into a binding.pry)
