# A batch script for downloading all ableton packs

## How to use

1. First clone the git repository and move to the folder

```bash
git clone https://github.com/RyoIkarashi/ableton-packs-downloader.git
cd ableton-packs-downloader
```

2. Save your cookies.txt by using [`cookies.txt`](https://chrome.google.com/webstore/detail/cookiestxt/njabckikapfpffapmjgojcnbfjonfjfg?hl=en) chrome extension into the folder you've cloned.

3. Edit the script and change the distination path

`download-packs.sh`

```sh
# Change /Path/to/your/ableton/plugins/folder to your own
DIST=/Path/to/your/ableton/plugins/folder
```

4. Finally run the script

```sh
chmod +x ./download-packs.sh
./download-packs.sh
```
