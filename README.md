openshift-goliath-websockets
============================

This is a port of goliath websocket example (https://github.com/postrank-labs/goliath) to openshift

Create a ruby-1.9 application

    rhc app create -a gws -t ruby-1.9

Add this repo as a remote upstream and pull from it

    cd gws
    git remote add upstream -m master git://github.com/mrunalp/openshift-goliath-websockets.git
    git pull -s recursive -X theirs upstream master

Access the application at:

    http://gws-{your_domain}.rhcloud.com:8000

