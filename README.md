# ailette
Raspberry Pi jukebox using AIY Voice Kit and Mopidy


# Build

Set up AIY Voice Kit:\
https://aiyprojects.withgoogle.com/voice/

Connect to Raspberry Pi using ssh following above AIY instructions.


# Install

Install Mopidy:\
https://docs.mopidy.com/en/latest/installation/debian/#debian-install

Install Mopidy Spotify extension:
```
sudo apt-get install mopidy-spotify
```

Install virtualenv:
```
sudo apt-get install virtualenv
```

Install python3.7 (for [mopidyapi](https://github.com/AsbjornOlling/mopidyapi)):\
https://gist.github.com/SeppPenner/6a5a30ebc8f79936fa136c524417761d

(Probably want to use latest instead of 3.7.0 though I haven't tested)


# Configure

Configure Mopidy service:\
https://docs.mopidy.com/en/latest/running/

Configure radio streams:
[...]

Configure Spotify:
[...]


# Setup project

Get repo:
```
cd ~/repos
git clone 
cd ailette
```

Create a virtualenv and install python packages:
```
virtualenv -p python3.7 .ve
. .ve/bin/activate
pip install -r requirements.txt
```


# Related

Multi-function standalone streaming music player using Raspberry Pi:
https://www.pimusicbox.com/

Use as wireless speaker with Spotify Connect:
https://github.com/dtcooper/raspotify
