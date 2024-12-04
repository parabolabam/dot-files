
git clone --branch config-update git@github.com:parabolabam/dot-files.git ~/.config


curl -fsSL https://gist.githubusercontent.com/parabolabam/9628ac3afae6984fd77e03cbdb78110c/raw/6f956dd641dde23312f76fc6652ac74d98dd3248/sync_os.sh | bash sync_os.sh

cd ~/.config
stow . // or stow . --adopt
