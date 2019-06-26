### APACHE DONT OWN ME ###

##### How to use this project #####

If you've ever tried to setup an instance of some cool, shiny project you know how much it sucks. This tries to make Superset not suck, by allowing you just literally docker-compose up and get going, no bullcrap, no extra commands.

##### Steps #####
1. Install docker and docker-compose
2. In this root directory run `docker-compose up`
3. Login with the user `admin1` and password `adminpass`
4. CHECK IT OUT SCREW TUTORIALS~~!

## NOT EASY THINGS ##
  * Currently, you have to `docker-compose down` after shutting down the repo because there are some kinks to work out.
  * CSV uploading doesn't work. probably some permissions thing.

###### Goals and Next Steps ######
1. Automatically upload csv's in a folder
2. Figure out why csv's can't be uploaded via gui
3. Configure postgres to use a column store extension for uploaded csvs for faster querying
4. Incorporate a tool that allows for joins among uploaded csvs.

