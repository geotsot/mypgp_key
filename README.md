
# My public pgp key

`key id: 2498FC9A92930928`

in bash use :

`wget -q https://raw.githubusercontent.com/geotsot/mypgp_key/main/mygpg.key && echo -n "key id:" && gpg --list-packets mygpg.key | awk '/keyid:/{ print $2 }' && gpg --import mygpg.key`

If you want to send me an encrypted e-mail use the previous key, use bash to send me an email: `gpg -e -a -r geotsot@gmail.com` and when you finish press `ctrl+D`

*Read me content inspired from [https://github.com/drazioti/my_public_key](https://github.com/drazioti/my_public_key)*
