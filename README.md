# Cluster_fstab
Creación de un cluster en VirtualBox
## 1.fstab
### Cluster
## DiscoA
### Crear las siguientes particiones 
Linux --> usamos el comando (fdisk /dev/sdb) (siendo sdb el primer disco)

partition type:
  p  primary (0 primary, 0 extended , 4 free)
  e extended
Select (default p): p
Partition number (1-4, default 1) :1
First sector (2048-20971519, default 2048) :
Using default value 2048
Last sector, +sectors or +size{K,M,G} (2048-20971519, default 20971519):1000000
0

command (m for help): n 

partition type:
  p  primary (1 primary, 0 extended , 3 free)
  e extended
Select (default p): e
Partition number (1-4, default 2) :2
First sector (1000001-20971519, default 1000001) :
Using default value 1000001
Last sector, +sectors or +size{K,M,G} (10000001-20971519, default 20971519):
Using default value 20971519

command (m for help): w
The partition table has been altered!

Called ioctl() to re-read partition table.
Syncing disks.
