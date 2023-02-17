# VeeamZIP
 # VeeamZIP delivers technology that lets you create backups of running VMs. With VeeamZIP, you have to specify only two things – the VM you want to backup and where your resulting backup file will go. It’s that easy! The backup will be deduplicated (within the single VM being backed up) and compressed, resulting in significantly lower backup storage requirements. Many people ask what benefit this will provide in terms of disk space when only a single VM is involved, when I use VeeamZIP on a single VM; the disk savings are usually about half that of the VM’s actual usage on disk.  The figure below shows a VeeamZIP ad-hoc backup being started:
# VeeamZIP is helpful when:
 # You need to update a VM. Users frequently take a VeeamZIP backup before making any changes to a VM, such as before applying updates or patches.
 # You need to archive a VM. It’s simple to create a deduplicated and compressed copy of a VM before removing it from your virtual infrastructure.

# You need to copy a VM to a remote host or test lab. VeeamZIP encapsulates VM configuration settings so you can easily transfer and run a VM in a different location.

# Powerful and flexible restores
# Veeam Backup Free Edition supports several data recovery scenarios, beginning with recovery of a VM file and going all the way to restoring an entire VM. The list includes:

# Restoring VM files (.vmdk, .vmx and others for VMware; .vhd, .vhdx, .xml and others for Hyper-V). Veeam Backup Free restores VM files directly from deduplicated, compressed backups without having to extract the VM from the backup.
# Restoring an entire VM. You can restore an entire VM to the same location or to a new location.
# Restoring VM disks (VMware). If a VM disk becomes corrupted by an OS failure or some other cause, you can simply restore the affected VM disk and connect it to the original or recovered VM.
# Restoring guest OS files. You can restore guest OS files for Windows FAT and NTFS file systems, and also ReFS with OS-level deduplication when running Windows Server 2012. Moreover, a special wizard and a virtual helper appliance provide support for 17 additional file systems. In all cases, Veeam Backup Free Edition is able to restore the guest files without having to extract the entire virtual disk image from the backup.
# Quick Migration (VMware)
 # Quick Migration lets you migrate live VMs between hosts or datastores without requiring clusters, shared storage or advanced functionality that is not available in lower-level hypervisor editions. Quick Migration works well even in environments with slow or high latency connections that prevent VMware vMotion and Hyper-V Live Migration from working!

# Additional v7 Features
 # In addition to offering enhanced functionality for existing capabilities, v7 also introduces brand new features. Here are seven of my favorites:

# 1. Native tape support: Regardless of the fact that tapes are often considered an evil, they can be a necessary evil because many datacenters continue to actively use them for archived or offsite backups. And this is understandable – tapes are portable, and long-term storage is inexpensive.