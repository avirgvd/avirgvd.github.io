
# About EasyPXE
EasyPXE simplifies PXE network boot process for OS deployment.
It reduces manual effort in setting up PXE services required for network-boot based OS deployment. The web-UI takes minimal inputs from the user and discovers most of the network settings automatically to configure the tool for PXE net-boot.

The tool is compatible with custom OS images created for optical media or USB media based OS deployment, making it easy to switch to network based OS deployment.

EasyPXE is a versatile tool supporting multiple formats of custom OS images. Refer to the "Supported OS Images" section for more details.

The tool can be installed on a Linux VM running in a Laptop or a server.

**EasyPXE Features**

- Intuitive Web-UI.
- Provisions OS images for network booting of PXE enabled client devices.
- Creates custom OS image by cloning drives of the reference client device.
- Deploys CentOS 7 over network using bootable ISO image.
- Deploys Windows 10 over network using the custom images created using MDT/LiteTouch.
- Deployes Windows 10 and Windows Server over network using bootable WinPE images.
- Generates PXE boot menu with boot items for all configured OS images.
- Uses HTTP for faster loading of boot images and reduced provisioning times.
- Supports UEFI as well as Legacy BIOS on client devices.
- Works with or without DHCP service in the network.
- In distributed mode, the OS images can be published from a single central instance of the tool.
- Site local instance of the tool pulls the required images from the central instance.

![PXE Boot using EasyPXE](easypxe.png)

