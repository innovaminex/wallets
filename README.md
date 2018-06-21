# Wallets

Requirements for Windows.

You need to download Visual C++ redistributable package from Microsoft https://www.microsoft.com/en-us/download/details.aspx?id=48145 . The configuration file and data directory is created automatically when you first run the wallet on Windows. There is no need to specify nodes as the INX Thunder network will announce nodes and other wallet connections from the network itself. 

Requirements for Linux and Linux Based ARM Devices.

For Linux, you require Boost libs and UPNP libs. Look at the build.unix under docs folder. Install the required components with "apt-get install libboost-all-dev libqrencode-dev libminiupnpc-dev -y" . If you wish to have a full native app built, simply follow the build instructions for Unix. It is highly recommended that native wallets are compiled on Linux platforms to avoid dependencies issues.

It is also possible to run INX Wallet 32bit Windows wallet on ARM 32bit native machines with ExaGear and Wine package. You can obtain ExaGear license and follow the setup guide from https://docs.eltechs.com/install-and-configure-exagear-desktop.

In case of your router configuration issues, you can manually add nodes to your wallet from the Debug console. Add a single node using "addnode tn0.innovaminex.com add" . This node will start adding more nodes for your wallet itself.

INX Development Team <p>
www.innovaminex.com
