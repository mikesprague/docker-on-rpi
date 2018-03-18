# :whale: Basic setup/configuration for Docker on a Raspberry Pi

```bash
# get/start the offical docker installer
curl -sSL https://get.docker.com | sh

# set docker to auto-start
sudo systemctl enable docker

# start the docker daemon
sudo systemctl start docker

# enable docker client
sudo usermod -aG docker pi

# note to user
echo "If you are connected via SSH, disonnect and reconnect now"
```
