# A batch script for downloading packs for Ableton Live 10

## How to use

1. First clone the git repository and move to the folder

```bash
git clone https://github.com/RyoIkarashi/ableton-packs-downloader.git
cd ableton-packs-downloader
```

2. Save your cookies.txt by using [`cookies.txt`](https://chrome.google.com/webstore/detail/cookiestxt/njabckikapfpffapmjgojcnbfjonfjfg?hl=en) chrome extension into the folder you've cloned.
* If you are not logged in, first login and then export `cookies.txt`

3. Run the script to install packs

| option | description |
| ---- | ----------- |
| -c   | path to your cookie.txt (**required**) |
| -o   | path to your download directory (**required**) |

```sh
chmod +x ./download-packs.sh
./download-packs.sh -c /path/to/cookie.txt -o /path/to/download/dir
```
