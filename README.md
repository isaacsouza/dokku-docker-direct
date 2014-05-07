# dokku-docker-direct

Issue Docker commands via dokku.

## Installation

```bash
cd /var/lib/dokku/plugins
sudo git clone git@github.com:heichblatt/dokku-docker-direct.git docker-direct
sudo dokku plugins-install
```

## Usage

Issue Docker command
```bash
docker-direct <docker-command>
dodi <docker-command>
```

## Example

View currently running containers:

```bash
ssh dokku@your_host docker-direct ps
```