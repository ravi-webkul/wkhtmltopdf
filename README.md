# wkhtmltopdf For Ubuntu(14 & 16)
wkhtmltopdf odoo supported version

# For Ubuntu: Use deb file and run below command
sudo dpkg -i wkhtmltox-0.12.1_linux-trusty-amd64.deb

# Copy files as –
sudo cp /usr/local/bin/wkhtmltopdf /usr/bin

sudo cp /usr/local/bin/wkhtmltoimage /usr/bin


# For Centos: Use rpm file and run below command
rpm -Uvh wkhtmltox-0.12.2.1_linux-centos7-amd64.rpm

# Restart Odoo server and then try again.

# wkhtmltopdf For Ubuntu 18.04

sudo wget https://github.com/wkhtmltopdf/wkhtmltopdf/releases/download/0.12.5/wkhtmltox_0.12.5-1.bionic_amd64.deb

sudo dpkg -i wkhtmltox_0.12.5-1.bionic_amd64.deb

sudo apt-get install -f

sudo ln -s /usr/local/bin/wkhtmltopdf /usr/bin

sudo ln -s /usr/local/bin/wkhtmltoimage /usr/bin

# wkhtmltopdf For Ubuntu 20.04

sudo apt-get install xfonts-75dpi
sudo wget https://github.com/wkhtmltopdf/packaging/releases/download/0.12.6-1/wkhtmltox_0.12.6-1.bionic_amd64.deb
sudo dpkg -i wkhtmltox_0.12.6-1.bionic_amd64.deb
sudo cp /usr/local/bin/wkhtmltoimage  /usr/bin/wkhtmltoimage
sudo cp /usr/local/bin/wkhtmltopdf  /usr/bin/wkhtmltopdf
