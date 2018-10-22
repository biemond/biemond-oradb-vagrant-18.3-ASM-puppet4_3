## Oracle Database 18.3 with ASM on NFS for Puppet >= 4.4

The reference implementation of https://github.com/biemond/biemond-oradb
optimized for linux, solaris

ASM is based on NFS

### Software ( 18.3 )
- https://www.oracle.com/technetwork/database/enterprise-edition/downloads/oracle18c-windows-180000-5066774.html

### Vagrant
Update the vagrant /software share to your local binaries folder

Startup the box
- vagrant up dbasm

Login
- vagrant ssh dbasm

### Accounts
- root password vagrant
- vagrant password vagrant, has sudo rights
- grid password oracle
- oracle password oracle

