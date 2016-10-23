# ansible


## Ansible Installation
```
$ easy_install --upgrade ansible
```

## Using Vagrant

Once this is set up, you can simulate our website on your local machine. Open the file '/etc/hosts' on your local machine and add the line `192.168.33.10 dev.cmucourseselection.com` (or any URL) and you can open our website in your browser.

## Vagrant Installation
We have already configured the necessary vagrant machines. However, if you wish to add your own, you may do the following.

Installing Vagrant and Virtual Box:
www.vagrantup.com
virtualbox.org

Go to vagrantcloud.com to find boxes.

```
$ vagrant box add <box_name>
```

To actually run vagrant machine, run

```
$ vagrant init <box_name>
$ vagrant up <box_name>
```

For additional information on vagrant machines see [this page](https://www.vagrantup.com/docs/).
