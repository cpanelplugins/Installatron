# Installatron

Installatron Plugin is installed as a plugin on supported web hosting control panel systems. To download and install on a server, select the control panel installed below.

# Installation

Execute the below commands from the SSH root command prompt. Select RPM for servers that support the RPM packaging standard, Debian for servers that support the Debian packaging standard, or select Standard for any type of server.

`wget https://data.installatron.com/installatron-plugin.sh`
`chmod +x installatron-plugin.sh`
`./installatron-plugin.sh -f`

Note: Installing without a license will limit use to one domain. Servers can be upgraded to unlimited domains simply by purchasing a license.

# Get started

Installatron Plugin is now ready to use in cPanel and WHM.

The main WHM account will see an Installatron Admin button in the Addons portion of the side menu.
Resellers will see an Installatron Admin button in WHM and an Installatron button in cPanel.
Website owners will see an Installatron Applications Installer button in cPanel.

# Import existing installations

Existing installations can be imported into the Installatron Plugin system using the one-click tool at Installatron Admin > Tools > Converter or this shell command:

`/usr/local/installatron/installatron --convert`

# Maintenance

A crontab process has been created to automate Installatron Plugin maintenance, including checking for Installatron Plugin and application updates.

Continue to the Advanced Usage FAQ for advanced usage information: https://installatron.com/docs/admin/advancedusage
