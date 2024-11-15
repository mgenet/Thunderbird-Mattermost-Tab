# Mattermost Tab
Unofficial Mattermost add-on for Thunderbird, it adds a button that opens a Mattermost tab in Thunderbird.
Forked from https://github.com/Era-Dorta/Thunderbird-Google-Keep-Tab.

#### Installing from sources
Download the repository, zip it, rename it to Mattermost.xpi and choose install addon from file in Thunderbird.

In linux the xpi file can be created with the following commands
* `git clone https://github.com/mgenet/Thunderbird-Mattermost-Tab`
* `cd ./Thunderbird-Mattermost-Tab`
* `VERSION=$(cat ./manifest.json | jq --raw-output '.version')`
* `zip -r "../Thunderbird-Mattermost-Tab-${VERSION}.xpi" *`
