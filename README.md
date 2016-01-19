Hotel Management Installation Steps

Note - Maker sure to enable "short_open_tag=On" in your 'php.ini' file.

1. Copy the unzipped project folder to www/htdocs location and change the project name to 'hotel' 

	OR
	
	Change the your project base_url name in app/config.php folder to the following
	
	$config['base_url']	= 'http://localhost/hotel_managment';

2. Create a database with name 'hotel' and Open 'Database' folder which is in project root folder and dump the 'hotel.sql' file to database using phpmyadmin or any other relavent tools.

	OR
	
	If you have given the name of the database other then 'hotel' then change the name of the database on app/database.php to the following
	
	$db['default']['hostname'] = 'localhost';
	$db['default']['username'] = 'root'; //DB username
	$db['default']['password'] = ''; //DB password
	$db['default']['database'] = 'hotel_managment'; //In case if your database name is 'hotel_managment'
	
3. Open browser with the the following url 
	localhost/hotel
	
	or 
	
	localhost/your_project_name
	
4. Now login with the following credentials

	username - channaveer
	password - channaveer

Note - Apart from Reservation option I have checked rest of the things which are working fine.

Happying Coding!
