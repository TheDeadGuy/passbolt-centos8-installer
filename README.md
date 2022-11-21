I don't know if this repo is still relevant or even being used. I am archiving it as the master repo from passbolt has been edited and improved to incorporate this repo's tasks. Repo is being archived

# passbolt-centos8-installer

Run the following commands found at https://help.passbolt.com/hosting/install/ce/centos-7.html

```
curl -L -o passbolt-ce-installer-centos-7.tar.gz https://www.passbolt.com/ce/download/installers/centos/latest
curl -L -o passbolt-installer-checksum https://www.passbolt.com/ce/download/installers/centos/latest-checksum
sha512sum -c passbolt-installer-checksum
tar -xzf passbolt-ce-installer-centos-7.tar.gz
```

Then download the files from my github and over-write the downloaded files. Once over-written, run this command:

```
sudo ./passbolt_ce_centos_installer.sh
```
