# dedica-plymouth-theme
dedica GmbH plymouth theme

## How to use

* ``cd /usr/share/plymouth/themes/``
* ``sudo git clone https://github.com/basseur/dedica-plymouth-theme.git dedica-gmbh``
* ``sudo update-alternatives --install /usr/share/plymouth/themes/default.plymouth default.plymouth /usr/share/plymouth/themes/dedica-gmbh/dedica-gmbh.plymouth 100``
* ``sudo update-alternatives --config default.plymouth``
* ``sudo update-initramfs -u -k all``

## Authors
* Written by: Jan Philipp Gölz <jan@dedica.team>
* Logo design by: Alfred Rehbach <mail@alfredrehbach.de>