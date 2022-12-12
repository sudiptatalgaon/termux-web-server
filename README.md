Install Termux web server and setup neccessary settings in your Termux Aap.

The document root is device accessible internal storage so you can easily manage your files.

Web server include Apache, Php, PhpMyAdmin, MariaDB Mysql Database, 

Start web server by running starjet command.

This will bring you to the Homepage of your server automatically.

pkg install git -y && cd ~/ && git clone https://github.com/sudiptatalgaon/termux-web-server && cd ~/termux-web-server && bash setup && cd ~/ && rm -rf termux-web-server
