# Apache2 Web Server - Kali Linux

A basic Apache2 web server set up in the Kali Linux terminal.

## Steps Taken

1. Updated system packages with apt update and apt upgrade
2. Installed Apache2 with apt install apache2
3. Started the service with systemctl start apache2
4. Verified the server by visiting the machine IP in Firefox
5. Navigated to /var/www/html and edited index.html with nano
6. Added custom HTML to the homepage
7. Disabled Apache2 on boot with systemctl disable apache2

## Files

- index.html — custom Apache2 homepage

## Notes

Server is manually started and stopped to prevent
unauthorized access when offline.
