To build the image:
docker build -t mathapp-development .

To run the container so it can be referenced in port 8010:
docker run -it --rm -p 8010:8010 -v $PWD/src:/go/src/mathapp mathapp-development

