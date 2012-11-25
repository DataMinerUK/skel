Vagrant Test
============

1 Download and install VirtualBox from http://www.virtualbox.org
2 Download and install Vagrant from http://vagrantup.com
3 Download the Vagrantfile from the following location and place it in a test directory:
    https://raw.github.com/DataMinerUK/infinite-interns/9ea138e33fe8ac7827c10e401fbaa16547ac3fca/vagrant/boxes/mysql/Vagrantfile
4 Ensure sure the file is called "Vagrantfile" and does not have any suffix.
5 Open a terminal in the test directory and run:
    vagrant up
  The path to the vagrant command may need to specified.
6 Download and install SequelPro from http://www.sequelpro.com.
7 Start SequelPro and Command-N to open a connection dialog if it is not already open.
8 Enter the following connection settings for the vagrant:
   * Host: 127.0.0.1
   * Username: root
   * Password: password
   * Port: 3306
9 Click connect and SequelPro should connect and present a clean database.
10 Have a play with SequelPro.
11 When you are finished, disconnect SequelPro and run the following in the console:
    vagrant destroy