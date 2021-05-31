### Building Custom Ansible Node Docker Images

#### You need to generate ssh keys as regular user(non-admin)
```
ssh-keygen
```
Accept all defaults by hitting Enter key.

The generated public key of that user must be copied into ubuntu-ansible and centos-ansible folders as shown below
```
cd ansible-docker-images
cp /home/jegan/.ssh/id_rsa.pub ubuntu-ansible/authorized_keys
cp /home/jegan/.ssh/id_rsa.pub centos-ansible/authorized_keys
```ubuntu-ansible
