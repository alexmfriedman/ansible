# ansible


## Ansible Installation
```
$ easy_install --upgrade ansible
```

We will be using Ansible 2.1.

## Using Vagrant

To run your vagrant machine, run
```
$ vagrant up
```

To provision with Ansible, run
```
$ vagrant provision
```

To halt vagrant machine, run
```
$ vagrant halt
```

If there is a problem, you can destroy your vagrant machine. Run
```
$ vagrant destroy
```

Note that you must specify a vagrant machine if there are multiple configurations in your current environment. However, since there is only one vagrant machine, we do not have to do so here.

Once this is set up, you can simulate our website on your local machine. Open the file '/etc/hosts' on your local machine and add the line `192.168.33.10 dev.cmucourseselection.com` (or any URL) and you can open the URL in your browser.

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
