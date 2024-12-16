```/bin/bash
Sync setup with:
https://gist.github.com/parabolabam/8a50bd7657691311b38b3455aa1da54e

To restore .zshr config clone this gist into your home directory:
https://gist.github.com/parabolabam/81c208bfac6979e1a762b7d7fb126353

```

git clone git@github.com:parabolabam/dot-files.git ~/.config

curl -fsSL https://gist.githubusercontent.com/parabolabam/9628ac3afae6984fd77e03cbdb78110c/raw/6f956dd641dde23312f76fc6652ac74d98dd3248/sync_os.sh | bash sync_os.sh

cd ~/.config
stow . // or stow . --adopt
