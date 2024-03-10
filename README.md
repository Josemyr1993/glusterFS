### GlusterFS 

GlusterFS é um prohjecto para implementação do conceito de "Storage Repplication", comporta mais componentes como:
- SAMBA
- SMB
- NFS
- Keep Alive
- Linux
- Windows

O conceito aplicado é que tanto para mounts Linux e path em Windows, todo o ficheiro criado no gluster01 deve replicar-se no gluster02;
Os servidores estão configurados para responderem a um único IP (VIP) que de modos que se um servidor estiver indisponível, o outro consegue servir aos clientes aplciando assim o conceito de HA no gluster;

![image](https://github.com/Josemyr1993/glusterFS/assets/86851766/e78729e3-0624-46ce-9fcb-a74b55b093ce)

