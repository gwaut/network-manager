network-manager
===============

The network-manager script enables or disables Ubuntu's desktop NetworkManager.

To disable Ubuntu's desktop NetworkManager:
>network-manager 0 

To enable Ubuntu's desktop NetworkManager:
>network-manager 1 

When re-enabling the Ubuntu's desktop NetworkManager, your OS might be unstable. Rebooting will fix the problem.

When Ubuntu's desktop NetworkManager is disabled, you have to configure your network interfaces in /etc/network/interfaces.

Tested on Ubuntu 12.04
