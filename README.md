# Keep-External-Speaker-Awake

### This is a small script to keep an external speaker awake in Ubuntu 22.04

* Clone repo in your `home` directory
* Execute `pip3 install -r requirements.txt` 
* Replace `dibyabiva` with your username in the file `keep_speaker_awake.service`
* Execute `sudo cp keep_speaker_awake.service /etc/systemd/system`
* Execute `sudo systemctl start keep_speaker_awake.service`
* Execute `sudo systemctl enable keep_speaker_awake.service`

This script will now automatically keep playing a blank mp3 file, keeping the speaker awake at all times.
