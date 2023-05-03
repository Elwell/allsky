# Allsky webcam - The great refactor version.

(Original README is presently [Over at README_upstream.md](README_upstream.md)).

## Grand Plan (in no particular order or consideration of difficulty)
* Run binaries from system standard locations (/usr/bin)
* Public web frontend should be webserver agnostic and play nicely with a dropin config file
* admin / config web pages should become a [cockpit package](https://cockpit-project.org/blog/cockpit-starter-kit.html)
* Installation shouldn't require user to run shell scripts, but prompt using standard debian dialogue
* oh and it should be packagesd as a .deb
* Config files in /etc/allsky/ and NOT JSON.

Suggestions welcome, this is going to be a long term project and is currently being worked on a debian testing (bookworm) install so that as many packages as possible come from packages, reducing the need to pip install as much as possible. Especially for slow to compile things (Waves to opencv, astropy etc)

