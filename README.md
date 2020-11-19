# Jolie Documentation

Docker image with Gitbook using the [xiroV/gitbook-plugin-highlight-jolie](https://github.com/xiroV/gitbook-plugin-highlight-jolie) plugin, to support Jolie syntax highlighting.

Build the image with

```
docker build -t jolie-docs . 
```

Then run it with

```
docker run --rm -it -p 8080:8080 -d jolie-docs
```

The Gitbook should then be accessible on [localhost:8080](http://localhost:8080).
