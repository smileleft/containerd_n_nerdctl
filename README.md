# containerd_n_nerdctl
containerd and nerdctl as docker alternative

# Install containerd
```
# 1. Download containerd binary from https://github.com/containerd/containerd/releases
# current latest version is 2.1.4 (2025-10-27)
sudo tar xvzf /usr/local containerd-2.1.4-linux-amd64.tar.gz

# make default config (/etc/containerd/config.toml)
containerd config default | sudo tee /etc/containerd/config.toml

