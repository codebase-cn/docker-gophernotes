### Docker Gophernotes

Built upon the fairly small micro-jupyter container image. Includes minimal libs to run gophernotes.

You can also just do ```bash docker pull danishabdullah/docker-gophernotes:latest```

In order to do one off session
```docker run --rm -p 8888:8888 danishabdullah/gophernotes:latest jupyter notebook --port=8888 --no-browser --ip=0.0.0.0```

This image is designed to be very small. Yet it is about 605 MB. If you know a way to make it smaller, file an issue and make a pull request. :)

