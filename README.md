# INX Wallets

Requirements for Windows.

You need to download Visual C++ redistributable package from Microsoft https://www.microsoft.com/en-us/download/details.aspx?id=48145 . The configuration file and data directory is created automatically when you first run the wallet on Windows. There is no need to specify nodes as the INX Thunder network will announce nodes and other wallet connections from the network itself. 

Requirements for Linux and Linux Based ARM Devices.

For Linux, you require Boost libs and UPNP libs. Look at the build.unix under docs folder. Install the required components with "apt-get install libboost-all-dev libqrencode-dev libminiupnpc-dev -y" . If you wish to have a full native app built, simply follow the build instructions for Unix. It is highly recommended that native wallets are compiled on Linux platforms to avoid dependencies issues.

It is also possible to run INX Wallet 32bit Windows wallet on ARM 32bit native machines with ExaGear and Wine package. You can obtain ExaGear license and follow the setup guide from https://docs.eltechs.com/install-and-configure-exagear-desktop.

In case of your router configuration issues, you can manually add nodes to your wallet from the Debug console. Add a single node using "addnode tn0.innovaminex.com add" . This node will start adding more nodes for your wallet itself.

Nodes for manual addition.

tn0.innovaminex.com <br>
tn1.innovaminex.com <br> 
tn2.innovaminex.com <br>
tn3.innovaminex.com <br>
tn4.innovaminex.com <br>
tn5.innovaminex.com <br>

Anti Censorship Network Access

Simply download Tor bundle and insert proxy for your wallet as 127.0.0.1 with port 9150 to access INX thunder network.<br>
Your wallet will automatically bypass any censorship to INX network. You have the option of adding the frontend node as "addnode dyzkv4gcknlkoecq.onion add" & "addnode fddbivpuea3auezw.onion add" under the debug console.

INX Development Team <br>
www.innovaminex.com
