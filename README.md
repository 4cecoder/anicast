# anicast
# ANIME from the terminal to TV in a single command

# Search for an Anime and beam to TV from ONLY YOUR terminal (macos/linux)

### Repo Cloning Commands
```bash
git clone --recursive https://github.com/4cecoder/anicast
cd anicast
```

### First run the build command 
```bash
./setup.sh
```

### search for an anime in cli 

# then cast it to a smart tv or other castable device

```bash
#usage
cast.sh <anime-title-query> <choose result number> <episode number>
```
### Just Wait for your anime selection to download and...

## Now you're beaming it!

### It should just start casting to whatever's currently castable on your local network

## Dependencies:
### Bruh you need ALL these packages too
Casting:
```
go
```
Anime Searching:
```
grep
sed
curl
openssl
jq
```
