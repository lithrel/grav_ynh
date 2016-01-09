# Grav for YunoHost

* http://getgrav.org/
* https://github.com/getgrav/grav

## Installation

From YunoHost admin panel:

1. Enter repository url https://github.com/lithrel/grav_ynh
2. Configure the app
3. Click install
4. Go to the url you configured

From command line:

`sudo yunohost app install -l grav https://github.com/lithrel/grav_ynh`

Options:

1. __Choose a domain for Grav__  
Domain for your installation (example.org).

2. __Choose a path for Grav__  
Path for your installation (/grav).

3. __Is it a public application ?__  
If public, everybody will be able to access your Grav instance (example.org/grav).

4. __Do you wish to install the Admin plugin ?__  
Grav has an optional admin panel, answer `Yes` if you want to use it.

5. __Use Yunohost SSOwat for admin connection ?__  
Only works if admin panel is installed.  
If `Yes`, an admin account will be automatically created when you first visit your Grav instance, and you will be redirected to the admin panel. your authentication will be handle by your YunoHost connection.  
If `No`, on your first visit to your Grav instance Grav will propose you to create a new user.


## Todo

- Currently only works on the root of a domain (path: `/`)
