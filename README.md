### Docker Gophernotes

Built upon the fairly small micro-jupyter container image. Includes minimal libs to run gophernotes.

You can also just do ```bash docker pull danishabdullah/docker-gophernotes:latest```

In order to do one off session
```docker run --rm -p 8888:8888 gophernotes jupyter notebook --port=8888 --no-browser --ip=0.0.0.0```