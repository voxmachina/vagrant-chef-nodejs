# Virtual machine running Ubuntu with Node

A boilerplate for Nodejs projects using Vagrant and Chef

## Dependencies

* [Vagrant](https://www.vagrantup.com/)
* [librarian-chef](https://github.com/applicationsonline/librarian-chef)
* Ruby version >= 2.1

## Howto

### Virtual machine
    librarian-chef install --verbose
    vagrant up

### Nodejs app
in the public/ folder is the actual Nodejs server example

	vagrant ssh
	cd /var/www/myapp/public
	npm install
	npm start
