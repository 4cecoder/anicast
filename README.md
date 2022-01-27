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

## search for an anime title in cli
1. Find the name of the anime and remember the query number (for dub or subbs choice)
2. test to see if the episode is reachable by this first command
3. find your episode number (will need for the next step)

``` ani-cli/./ani-cli <name> ``` 

### once you know know the cli name and episode number 
# Then it is time to get casting
## cast it to a smart tv or other castable device

```bash
#usage
./cast.sh <anime-title-query> <choose result number> <episode number>
```
### Just Wait for your anime selection to download and...

## Now you're beaming it!

### It should just start casting to whatever's currently castable on your local network

## Dependencies:
## *Bruh* 
### you NEED ALL these normal linux packages working: 
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
