Convert html to pdf using dockerized chrome headless
====================================================

Upon executing this role a wrapper script `/usr/bin/html-to-pdf` will be provided.

It takes two arguments:
 * The url to convert
 * The output filename
 
 
## Security

Remember that normal users cannot run `docker` because this would allow outright root privelege escalation.

You can use sudoers to allow a specific users sudo access to this script. 