# coincheck-price-viewer
A tiny coincheck price viewer for bitbar

## Installation

Make sure your `/usr/local/bin/node -v` is **over v7.6.0** which supports `async`/`await`

```bash
# move to a bitbar plugin directory
cd /path/to/bitbar-plugin-directory/
# download the source
git clone https://github.com/RyoIkarashi/coincheck-price-viewer.git
# move to the directory and install node moduels
( cd coincheck-price-viewer && yarn install )
# add a symlink to (make sure you're in a bitbar plugin directory)
ln -s ./coincheck-price-viewer/coincheck.5s.js
```

## Add your own `access_key` and `secret_key`

Edit `env.json` and replace `<YOUR_ACCESS_KEY>` and `<YOUR_ACCESS_SECRET_KEY>` with yours.

## Screenshot
![screen shot 2017-10-31 at 15 53 15](https://user-images.githubusercontent.com/5750408/32211052-25739bd4-be54-11e7-8d99-e65b1fc00d41.png)

## License
MIT

If you feel this little tool gives you some value, tips are always welcome at the following addresses!
- Bitcoin: 1DrLPjzmNHtkdBstd82xvCxGY38PnKauRH
- Mona:    MC7XMmi1YXoJH19D1q4H8ijBkdvarWBTMi
