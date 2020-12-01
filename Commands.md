
# How to mount the share folders:
1. *mount shared folders - vmware*
2. *sudo vmhgfs-fuse .host:/ /mnt/hgfs/ -o allow_other -o uid=1000*
3. *sudo mount -t vmhgfs .host:/ /mnt/hgfs (Use this if there is no hgfs folder in the /mnt directory )*
4. *alias mountwin='mount -o loop,ro,show_sys_files,streams_interface=windows'*