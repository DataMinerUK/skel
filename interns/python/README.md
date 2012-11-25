Vagrant Test
============

1 Download and install VirtualBox from http://www.virtualbox.org
2 Download and install Vagrant from http://vagrantup.com
3 Download the Vagrantfile from the following location and place it in a test directory:
    https://raw.github.com/DataMinerUK/infinite-interns/ca8dc31b3a57eae301de3d455d56859cbabed35a/vagrant/boxes/python/Vagrantfile
4 Ensure sure the file is called "Vagrantfile" and does not have any suffix.
5 Open a terminal in the test directory and run:
    vagrant up
  The path to the vagrant command may need to specified.
6 Connect to the guest OS in the terminal by running:
    vagrant ssh
7 Then start the ipython-notebook server on the guest OS using:
    ipython notebook --ip 0.0.0.0
8 Go to http://localhost:8888 and check that ipython-notebook is available.
9 To stop iPython hit control C
10 To get off the vagrant type exit or hit control D
11 When you are finished, run the following in the console:
    vagrant destroy
