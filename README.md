# rtv-sccmhunter

## Tools of the Trade
* SCCMHunter - [https://github.com/garrettfoster13/sccmhunter](https://github.com/garrettfoster13/sccmhunter)
* Impacket - [https://github.com/fortra/impacket](https://github.com/fortra/impacket)
* Python VirtualEnv - [https://virtualenv.pypa.io/en/latest/](https://virtualenv.pypa.io/en/latest/)
* WireGuard - [https://www.wireguard.com/](https://www.wireguard.com/)

## Installing Your Tools
### VirtualEnv
```
sudo apt install virtualenv
```
### SCCMHunter
```
git clone https://github.com/garrettfoster13/sccmhunter
virtualenv --python=python3 ./sccmhunter
cd sccmhunter
source bin/activate
pip3 install -r requirements.txt
```
### Impacket
```
git clone https://github.com/fortra/impacket
virtualenv --python=python3 ./impacket
cd impacket
source bin/activate
pip3 install .
```
## WireGuard
```
sudo apt install wireguard
```

## Connecting to the Lab
* Download your student WireGuard .conf file
* Verify you can reach the 10.x.10.10-15 hosts
```
sudo cp studentX.config /etc/wireguard/wg0.conf
sudo wg-quick up wg0
```
