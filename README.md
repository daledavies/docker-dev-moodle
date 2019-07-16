# Docker LAMP Environment for Moodle Development

**Docker development environment with Apache, PHP and MySQL...**

* Installs and configures Xdebug in the PHP container
* Includes launch.json config for VS Code with correct path mappings for Xdebug
* Includes moodledata directory for Moodle
* Creates a persistent data directory for MySQL when built.
* Exposes ports 80 and 3306 to the host. 

To use just build with Docker Compose and put Moodle's code (or any PHP files really) in the html directry.
