# bourne_again
Bash scripts for fun.

## General setup
In bash shell (Terminal on OS X):
```
$ cd <desired/home/your/copy/of/repo>
$ git clone https://github.com/nosrettep/bourne_again.git
$ cd bourne_again/scripts
$ chmod +x *
$ echo "PATH=${PATH}:<path/to/your/repo/bourne_again/scripts>"
```
### crypt
Usage: `$ crypt <amt_spent> <eos_held> <eth_held>`
-  `<amt_spent>` is the total amount invested (minus any previously cashed out money, in $USD).
-  `<eos_held>` is the number of EOS coins currently owned.
-  `<etc_held>` is the number of ETC coins currently owned.
-  `<btc_held>` is the number of BTC coins currently owned.
-  `0` is a valid number.
