# Custom fluentd docker image
This is a custom docker image based on the latest official fluentd debian image. Image contains added elasticsearch plugin to store logs and output them on kibana.
## Usage
Pull the image from docker hub:
```
docker pull hitmanx/fluentd
```
## Note
Make sure both elasticsearch and kibana are installed and configured on your system prior using this image, or just create a docker compose file with all mentioned services and run it to create all services at once.
