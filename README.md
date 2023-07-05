# glowing-robot
    
### How to run
* If we already have keys:
    * docker-compose up
* If we do not already have keys:
    * `cd centos7`
    * Create a key ssh key, named `remote-key` `ssh-keygen -f remote-key`
    * Can use the private key in jenkins container
    * `cd ../` , and then: `docker-compose up`

#### To Note: 
* If I end up storing a ssh key in this repo it is so I can go back for reference. It is not used by anyone or anything, other than this project.
