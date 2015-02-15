<h1>Homeworks for course M101JS: MongoDB forn Node.js developers </h1>


<h2>To install MongoDB on Mac OS X </h2>

<h3>Versions:</h3>
<h3>- MongoDB 2.6.7</h3>
<h3>- Mac OS X 10.10.2</h3>


<strong> A. Get MongoDB from official website and extracts it:</strong>

	$ cd ~/Download

	$ tar xzf mongodb-osx-x86_64-2.6.7.tgz

	$ sudo mv mongodb-osx-x86_64-2.6.7 /usr/local/mongodb

<strong>B. Create the folder to write/store data; create folder and assign proper permission:</strong>

	$ sudo mkdir -p /data/db
	
	$ sudo chown NAME_USER /data/db

<strong>C. To access Mongo’s commands easily add mongodb/bin to $PATH, create a ~/.bash_profile file and assign /usr/local/mongodb/bin to $PATH environment variable, .</strong>

	$ cd ~

	$ pwd

	/Users/NAME_USER

	$ touch .bash_profile

	$ vim .bash_profile
 <strong> add  this: </strong>
 	
 	export MONGO_PATH=/usr/local/mongodb
 		
	export PATH=$PATH:$MONGO_PATH/bin
 
<strong>D. Restart terminal</strong>
 
	$ mongo -version
	
	MongoDB shell version: 2.6.7



