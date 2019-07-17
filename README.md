# fscompilescripts
Scripts I use to compile FS on linux and what not.

These scripts are provided **WITHOUT SUPPORT** and **are not official Firestorm development scripts**. I am only posting them for convenience purposes.

# Setup
```bash
git clone https://github.com/FelixWolf/fscompilescripts.git
mv fscompilescripts firestorm
cd firestorm
hg clone http://hg.phoenixviewer.com/phoenix-firestorm-lgpl
hg clone http://hg.phoenixviewer.com/fs-build-variables
```

You should now have this structure inside the firestorm directory:
```
phoenix-firestorm-lgpl/
fs-build-variables/
build
configure
install
backup
run
showdiff
```

Open up `configure` and change `BUILD_CHANNEL` to whatever your own channel.

# Usage
## Configure
Edit the script to add your channel and run it once to configure optimal settings(IMO)

## Build
Run this and it will build the viewer for you

## Install
This will install firestorm to `/opt/firestorm/`

## Backup
This will copy the current install from `/opt/firestorm/` to `/opt/firestorm.backup/` should something go horribly wrong and need to restore it

## Run
This runs the build without installing it, also enables GDB.

## Showdiff
Shows current diffs from them main branch.
