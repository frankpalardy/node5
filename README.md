## Get the code to run on your machine

Pre-requisites:

* Git installed
* A command line interface capable of running Git commands
* Node v11 installed

To get the code for a specific branch:

`$ git clone -b branch-name https://github.com/cliveharber/gettingMean-2.git`

Then change into the folder the git clone command will create:

`$ cd getting-MEAN-2`

And finally install the dependencies:

`npm install`

## Getting the code via Docker

Pre-requisites:

* Docker

To get the code for a specific branch:

`$ git clone -b branch-name https://github.com/cliveharber/gettingMean-2.git`

Then change into the folder the git clone command will create:

`$ cd getting-MEAN-2`

And finally run the docker containers

`make build`

To remove the containers when complete

`make destroy`

