# 手动切换BBR内核，可以有效防止AWS换内核后失联

## Debian9, v4.14, install kernel from release.
```
bash <(wget --no-check-certificate -qO- 'https://raw.githubusercontent.com/MoeClub/BBR/master/install.sh')
```

## Debian9, v4.14, build kernel from source.
```
bash <(wget --no-check-certificate -qO- 'https://raw.githubusercontent.com/MoeClub/BBR/master/build.sh')
```


