# Carouches - Rest API server

This is a fork of The Guillotina REST API aNGular Environment, this is firstly for the backend (Guillotina) as Grange provides a really convienent setup.
It is basically Grange at the moment, but it is likely to branch significantly over time.

For more information about Grange visit the [original guillotina/grange repo](https://github.com/guillotinaweb/grange)

# Assumptions
- You have docker and docker-compose installed

# Getting started
Make sure you have docker and docker-compose installed.

To get started check out the code and run the following:
```
git clone https://github.com/alteroo/carouches
```

Then start it
```
cd carouches
./start.sh
```

or if you prefer a lengthier more explicit command

```
cd carouches
docker-compose -f g-api/docker-compose.yaml up
```
It will launch the service on port 8080.

You can access it by visiting http://localhost:8080



# API
Visit https://localhost:8080/api
Then click `Authorize`

Use the default credentials:

root:root
