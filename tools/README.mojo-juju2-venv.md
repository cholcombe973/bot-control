# Install MOJO in a Python Virtual Env for Juju 2.x

```
# Clone the tool to a tools directory
mkdir -p /home/ubuntu/tools
git clone https://github.com/openstack-charmers/bot-control /home/ubuntu/tools/bot-control
cd /home/ubuntu/tools/bot-control/tools

# Build venv
cd mojo-juju2-venv
tox -e mojo

# Source venv and use it
. .tox/mojo/bin/activate
mojo --version
```
