# Docker LAMP Environment for Moodle Development

**Docker development environment with Apache, PHP and MySQL...**

* Installs and configures xdebug in the php container
  * Includes Visual Studio Code launch.json with correct path mappings
* Includes moodledata directory for Moodle
* Creates a persistent data directory for MySQL when built.
* Exposes ports 80 and 3306 to the host. 

To use just build with Docker Compose and put Moodle's code (or any PHP files really) in the html directry.
