# Credits:
This project is a simple modification from Art of Wifi project to create vouhcers. 
Here is de original project https://github.com/Art-of-WiFi/UniFi-API-client

# Modifications:
The modifications is:
 - Added a in create_voucher.php, two super global variables named as $user and $password, just to receive through POST, the user name and passowrd for authenticate on the controller and create voucher.
 
 # How to Use:

 - In the config.php file, set the full URL from your controller on the variable $controllerurl and the controller version on $controllerversion. 
 - In the create_voucher.php set de value from your variable $site_id with the default site name from your unifi controller.
