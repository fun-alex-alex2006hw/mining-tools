# mining-tools
-------------
tools used for mining with CPU

## supported platforms
-------------
- osx and linux:
-- nheqminer with sample config for slushpool
-- xmr with sample config for monero Ocean

## support development
- BTC: 1KCuz54kYMDUJxqTLRCzLsv1HjHQnqp631
- XMR: 489A74o7uKAfP26uxxFrtq8ttKZfZFfuc44oTyXBAWVecwmSAg1niZVVDVxSRmcyuShnbTqXBzQmCPxb5aoaWX6rAhiNmbL

## usuage
- monero mining
```
# enable hugepage
sudo echo 128 > /proc/sys/vm/nr_hugepages
echo always > /sys/kernel/mm/transparent_hugepage/enabled
sysctl -w vm.nr_hugepages=128
# mining
sudo ./monero
```
- zcash mining
```
# mining
sudo ./slushbug
```
