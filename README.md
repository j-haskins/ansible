# ansible

For testing with a windows/WSL host acting as a control node (unsupported / non-production)

wsl --install
reboot or wsl --shutdown
wsl.exe --list --online
wsl.exe --install <Distro>

bash
sudo apt install software-properties-common
sudo add-apt-repository --yes --update ppa:ansible/ansible
sudo apt install ansible -y
sudo apt install python3-pip

Verify Ansible installation
ansible --version

