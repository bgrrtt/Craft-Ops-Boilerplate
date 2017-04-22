# Installation

### Prerequisites for Host Machine
- [Vagrant 1.9](https://www.vagrantup.com) and [VirtualBox](https://www.virtualbox.org/wiki/Downloads)
- [vagrant-hostsupdater](https://github.com/cogitatio/vagrant-hostsupdater)
- [vagrant-vbguest](https://github.com/dotless-de/vagrant-vbguest)

### Step 1. Clone!

```
git clone https://github.com/bgrrtt/craft-vm.git PROJECT_NAME
```

### Step 2. Change directory into your project and open it with a text editor (like [atom](https://atom.io/)).
```
cd PROJECT_NAME && atom .
```

### Step 3. In the `Vagrantfile` set:
  - **`DOMAIN_NAME`** to a locally unique domain for your project. Defaults to 'craft'.
  - **`LOCAL_IP`** to a nonconflicting address between 192.168.20.10 and 192.168.255.255.

### Step 4. [Download Craft CMS](https://buildwithcraft.com/latest.zip?accept_license=yes), unzip, and move `craft/app` into `PROJECT_NAME/craft`.

### Step 6. Start your new Craft VM:
```
vagrant up
```
### Step 7. Wait for the installation playbook to run. Hmmm, [what to do](https://github.com/bgrrtt/craft-vm/wiki)?

### Step 8. Enter the machine:
```
vagrant ssh
```

## Visit [http://craft.dev/admin](http://craft.dev/admin) to finish installation!

Thanks to [@pixelandtonic](https://github.com/pixelandtonic), [@khalwat](https://github.com/khalwat), and [@geerlingguy](https://github.com/geerlingguy) for their work and influence.
