# monero-wallet-flatpak
Flatpak buildfiles for the Monero Core Guil Wallet

To test this, do:
```
make
flatpak --user remote-add --no-gpg-verify local-monero repo
flatpak --user install local-monero org.getmonero.Wallet
```
