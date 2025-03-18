# wand

Wand makes it easy to configure dash, houdini and a media server utilizing docker & docker-compose.

> [!NOTE]
> This was not made to be ran on WSL. For that, use the original repository.

## Installation script
**Step 1** run the script
```bash
bash <(curl -s https://raw.githubusercontent.com/isylveon3000/wand/master/install.sh)
```
**Step 2** Answer Questions which are:
* Database password (Leave blank for random password)
* Hostname (example: `clubpenguin.com`) (Leave empty for localhost)
* External IP Address (Leave empty for localhost)
**Step 3** Run and enjoy.
Run this command:
```bash
$ cd wand && sudo docker-compose up
```
