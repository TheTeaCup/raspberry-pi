# raspberry-pi
just some scripts i used for my raspberry pi


# Installing MUTT
- install command: `sudo apt install mutt`
- make directories: `
mkdir -p .mutt/cache/headers
mkdir .mutt/cache/bodies`

###  Settung up Configuration
- create a new file: `nano .mutt/muttrc`
- past this in the the file you just created [config](mutt-config.txt) <br/>
^ note: this uses gmail

- test the emailing service: `echo "Email test message body" | mutt -s "Subject here" email@example.com`
