# Sei-1.0.7beta-postfix


# 836963.cü bloğa ulaşanlar güncelleme yapsın.

```
cd $HOME
rm $HOME/sei-chain -rf
git clone https://github.com/sei-protocol/sei-chain.git
cd $HOME/sei-chain
git checkout 1.0.7beta-postfix
make install
mv ~/go/bin/seid /usr/local/bin/seid
systemctl restart seid && journalctl -fu seid -o cat
```
