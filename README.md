### Step1: install git
```
sudo su -
yum update -y
amazon-linux-extras install ansible2 -y
yum install -y git
git clone https://github.com/HaneeshDevops/Master_config_repo.git
cd Mater_config_repo
ansible-playbook install_tools.yml --connection=local

```
