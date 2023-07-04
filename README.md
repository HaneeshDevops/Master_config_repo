### Step1: install git
```
sudo su -
yum update -y
amazon-linux-extras install ansible2 -y
ansible --version
yum install -y git
git --version
git clone https://github.com/HaneeshDevops/Mater_config_repo.git
cd Mater_config_repo
ansible-playbook install_tools.yml --connection=local
```
