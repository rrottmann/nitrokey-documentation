Nitrokey Storage, Windows
=========================

.. contents:: :local:

.. toctree::
   :maxdepth: 1
   :glob:
   :hidden:

   *

1. Connect your Nitrokey to your computer and confirm all dialogs so that the USB smart card device driver gets installed almost automatically.

.. note::

   Windows may fail to install an additional device driver for the smart card. Its safe to ignore this warning.

2. Download and start the `Nitrokey App <https://www.nitrokey.com/download>`_. Perhaps you want to store it on the unencrypted partition of your Nitrokey Storage. There won’t open a window, but an icon appears in the system tray (see screenshot below). Please right-click on this icon to use all the options of the App.

.. figure:: ./images/Windows10-Systemtray.png
   :alt: img1


3. Open the About window from Nitrokey App’s menu and check if you have the `latest firmware <https://github.com/Nitrokey/nitrokey-storage-firmware/releases>`_ installed. If it’s not the latest, please
   `update <firmware-update.html>`_.

4. Use the Nitrokey App to change the default User PIN (default: 123456)
   and Admin PIN (default: 12345678) to your own choices.

Your Nitrokey is now ready to use. 

.. note::

   For many use cases described, it is necessary to have either OpenPGP or S/MIME keys installed on the device (see below).

Key Creation with OpenPGP or S/MIME
-----------------------------------

There are two widely used standards for email encryption. While OpenPGP/GnuPG is popular among individuals, S/MIME/x.509 is mostly used by enterprises. If you are in doubt which one to choose, you should use OpenPGP.

-  `Instructions <openpgp.html>`_ for using the OpenPGP standard with the Nitrokey

-  `Instructions <smime.html>`_ for using S/MIME with the Nitrokey
