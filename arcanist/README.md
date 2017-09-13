Dockerized Arcanist
===================

[Arcanist](https://github.com/phacility/arcanist) is a CLI for [Phabricator](https://www.phacility.com/phabricator/).
It is quite tricky to install, specially to local system.

Here you can find Docker file and bash script to call arc like is it installed locally.

Security declaimer
------------------
This solution exposes whole home directory of current user to container.
Make sure that your are using it on trusted docker environment (means local one) only.
