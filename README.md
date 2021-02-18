# Install custom Geotrek instance

- Install docker on your server
- On your server pull this repo `git pull https://github.com/Weegle99/geotrek-customization.git`
- Update the files in the customization folder acccording to your structures
- Build the docker image `docker build -t geotrek-rando .`
- Run the docker image `docker run -d -p {YOUR_PORT}:80 geotrek-rando`

Your website is now available to the adress of your server

To configure nginx, please visit this link
