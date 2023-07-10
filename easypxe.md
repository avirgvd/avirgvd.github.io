
# About EasyPXE
EasyPXE simplifies PXE network boot process for OS deployment.
It reduces manual effort in setting up PXE services required for network-boot based OS deployment. The web-UI takes minimal inputs from the user and discovers most of the network settings automatically to configure the tool for PXE net-boot.

The tool is compatible with custom OS images created for optical media or USB media based OS deployment, making it easy to switch to network based OS deployment.

EasyPXE is a versatile tool supporting multiple formats of custom OS images. Refer to the "Supported OS Images" section for more details.

The tool can be installed on a Linux VM running in a Laptop or a server.

**EasyPXE Features**

- Intuitive Web-UI simplifies PXE services setup processes.
- Provisions OS images for network booting of PXE enabled client devices.
- Creates custom OS image by cloning drives of the reference client device.
- Deploys CentOS 7 over network using bootable ISO image.
- Deploys Windows 10 over network using the custom images created using MDT/LiteTouch.
- Deployes Windows 10 and Windows Server over network using bootable WinPE images.
- Customize PXE boot menu with multiple boot entries for offering multiple OS deployment options on the client device.
- Utilizes iPXE for faster loading of boot images with HTTP as TFTP can be very slow for large OS images.
- Uses HTTP for faster loading of boot images and reduced provisioning times.
- Supports UEFI as well as Legacy BIOS on client devices.
- Works with or without DHCP service in the network.

### Configuring PXE Boot Menu Entries using EasyPXE Web-UI
The PXE Boot menu items for different OS installations can be easily added using Web-UI.
![PXE Boot using EasyPXE](easypxe.png)



