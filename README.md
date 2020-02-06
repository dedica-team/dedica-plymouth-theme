# dedica-plymouth-theme
dedica GmbH plymouth theme

## How to use

* ``cd /usr/share/plymouth/themes/``
* ``sudo git clone https://github.com/basseur/dedica-plymouth-theme.git dedica-gmbh``
* ``sudo update-alternatives --install /usr/share/plymouth/themes/default.plymouth default.plymouth /usr/share/plymouth/themes/dedica-gmbh/dedica-gmbh.plymouth 100``
* ``sudo update-alternatives --config default.plymouth``
* ``sudo update-initramfs -u -k all``

## Authors
* Written by: Alberto Milone <alberto.milone@canonical.com>
* Adapted to budgie-remix by: HEXcube <hexcubed@gmail.com> and David Mohammed <foss.freedom@gmail.com>
* Adapted to TUXEDO Computers by: Vinzenz Vietzke <tux@tuxedocomputers.com>
* Based on the example provided with the "script plugin" written by Charlie Brej <cbrej@cs.man.ac.uk>
* Question stuff written by Markus Waas <mail@markuswaas.de>
* Adapted to dedica GmbH by: Jan Philipp Gölz <jan@dedica.team>
* Logo design by: Alfred Rehbach <mail@alfredrehbach.de>