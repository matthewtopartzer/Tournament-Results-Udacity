This code generates a Swiss Style tournament from the tournment.py file

//// Required Files
 - VirtualBox installation (https://www.virtualbox.org/wiki/Downloads)
 - Vagrant installation (https://www.vagrantup.com/download)
 - Clone the VM with this link, or just download the file, and put in select directory: (git clone http://github.com/udacity/fullstack-nanodegree-vm)

//// This link gives an overview of starting the Vagrant machine: (https://www.vagrantup.com/docs/getting-started/)

To run the test suite (exercising all of the Python functions for the tournament database):

//// These instructions are based on the current files, which are already included in the /Tournament-Results-MAIN directory
 1. cd tournament-results-main/vagrant/tournament
 2. vagrant up
 3. vagrant ssh
 4. cd tournament-results-main/udacity-tournament-results
 5. psql -f tournament.sql 
 6. python tournament_results.py