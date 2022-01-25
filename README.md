# anicast
# From terminal to TV
# Search Anime and beam to TV from Cli (macos/linux)

### First run the build command 
```bash
./setup.sh
```

### search for an anime in cli 

# then cast it to a smart tv

```bash
#usage
cast.sh <anime-title-query> <choose result number> <episode number>
```
## Now you're beaming it!

### It should just start casting to whatever's currently castable on your local network

## Dependencies:
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
