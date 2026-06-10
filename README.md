Launch an EC2 instance (Amazon Linux 2 or Ubuntu) in a public subnet.

Allow HTTP (port 80) and SSH (port 22) in the security group.

Connect to the instance using SSH.

Install a web server (Nginx or Apache).

Clone the static site from GitHub:

git clone https://github.com/usman-30/Mini-Finance-Static-web.git
Copy the site files to the web server’s root directory (e.g., /var/www/html).

Start the web server and ensure the website is accessible via the EC2 public IP.
