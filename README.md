# Price Calculator for Cloud Hosting
https://www.cloudorado.com/

# qemu-guest-agent(for Linux)
sudo apt install qemu-guest-agent \
sudo systemctl start qemu-guest-agent \
sudo systemctl enable qemu-guest-agent 


# Proxmox VE 
https://www.proxmox.com/en/ \
Admin Guide \
https://pve.proxmox.com/pve-docs/pve-admin-guide.html \
https://www.proxmox.com/en/downloads/proxmox-virtual-environment/documentation \
FAQ \
https://www.proxmox.com/en/downloads/proxmox-virtual-environment/agreements/proxmox-ve-subscription-agreement \
https://forum.proxmox.com/threads/what-is-the-differences-between-the-paid-and-free-version-of-proxmox.142951/ \
https://forum.proxmox.com/threads/what-are-limitations-of-the-free-version.113434/ \
https://forum.proxmox.com/threads/does-proxmox-still-offer-a-fully-free-version.146066/#:~:text=You%20can%20install%20Proxmox%20without,you%20chose%20to%20install%20updates). \
Proxmox Training \
https://www.youtube.com/watch?v=5j0Zb6x_hOk&list=PLT98CRl2KxKHnlbYhtABg6cF50bYa8Ulo&ab_channel=LearnLinuxTV \
https://www.linuxtechi.com/install-proxmox-ve-on-bare-metal/ \
System Requirements \
https://www.proxmox.com/en/proxmox-virtual-environment/requirements

# 15 Things You MUST DO After Installing Proxmox
https://www.youtube.com/watch?v=5kvouUIn5Zg&ab_channel=SkillsBuildTraining 

# Install and Config
https://www.starwindsoftware.com/blog/proxmox-ve-configure-a-ceph-storage-cluster/ \
https://nolabnoparty.com/en/proxmox-configure-high-availability-ha/ \
https://www.youtube.com/watch?v=-qk_P9SKYK4&t=578s&ab_channel=VirtualizationHowto 


# Repo Config
https://www.youtube.com/watch?v=bUD1fN3aT9U&ab_channel=HomeTechAutomation \
https://www.youtube.com/watch?v=DzHRhu3On7o&ab_channel=VirtualizationHowto

# Proxmox CLI Commands Every Admin Should Know
https://www.nakivo.com/blog/top-10-proxmox-cli-commands/

UI/UX \
https://gist.github.com/yuna0x0/6e5345b019a80de733f375b71f4d3917 \
https://forum.proxmox.com/threads/change-the-logo.109477/ \
https://forum.proxmox.com/threads/customise-login-page-and-logos.141855/ \
Main File Path \
/usr/share/pve-manager/ \
Logo Path \
/usr/share/pve-manager/images \
Text Login Box \
/usr/share/pve-manager/js/pvemanagerlib.js \
Banner Text \
index.html.tpl \
Restart Proxmox VE \
$systemctl restart pveproxy 
# Disable Proxmox VE Subscription Notification
https://www.youtube.com/watch?v=mQGB4hL2_ZQ&ab_channel=TechTutorials-DavidMcKone \
https://johnscs.com/remove-proxmox51-subscription-notice/ \
https://www.youtube.com/watch?v=dOC8dIjuJsI&ab_channel=CloudywithArnold \
https://bobcares.com/blog/proxmox-disable-subscription-warning/

# User Management
https://www.youtube.com/watch?v=DLh_j1CAj44&t=275s&ab_channel=ElectronicsWizardry \
https://pve.proxmox.com/wiki/User_Management \
https://www.youtube.com/watch?v=frnILOGmATs&ab_channel=LearnLinuxTV 

# Backup/Snapshot Proxmox with ZFS
zfs list \
zfs snapshot rpool/ROOT/pve-1@os-backup-$(date +%Y%m%d) \
zfs list -t snapshot \
zfs rollback rpool/data@backup-20250101

# CMP for Proxmox \
https://proxcp.com/index \
https://hostbillapp.com/ \
https://www.virtualizor.com/ \
https://www.virtualizor.com/docs/install/install-proxmox/ \
https://bennetgallein.de/shop/proxmox_control_panel-34

Storage Technology \
https://www.blockbridge.com/proxmox/

# Proxmox Backup
https://pbs.proxmox.com/docs/ \
https://www.youtube.com/watch?v=wv9v9HMZJNY&ab_channel=DistroDomain

# VPS/Cloud Hosting Service in Myanmar
https://mpt.com.mm/en/business-home/b2b-cloud-service/ \
https://www.global-dms.com/virtual-private-servers-vps-myanmar/ \
https://www.shwehosting.com/VPS-hosting/ \
https://www.netscriper.com/VPS-hosting/ \
https://www.worldwidemyanmar.com/vps-hosting/ \
https://cyberwings.asia/ \
https://www.gtmh-telecom.com/cloud-services/virtual-private-server/ \
https://shop.mtg.com.mm/vps-hosting.php?language=myanmar \
https://www.globalnet.com.mm/vps/ \
https://www.zeus.com.mm/ \
https://hosting.z.com/mm/private-hosting/ \
