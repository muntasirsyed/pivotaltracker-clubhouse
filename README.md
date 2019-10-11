**This is a work in progress to provide an updated (& fully working) pivotaltracker to clubhouse importer script.**

# pivotaltracker-clubhouse
Simple tool to transfer stories from Pivotal Tracker to Clubhouse.

## Python Package Dependencies
I'm assuming you'll use pip to install them.
* requests 2.7.0 or above

## Usage
```
usage: pivotaltracker-clubhouse [-h] --ptoken PTOKEN --ctoken CTOKEN
                                --pproject PPROJECT --cproject CPROJECT

optional arguments:
  -h, --help           show this help message and exit
  
required arguments:
  --ptoken PTOKEN      The app token of the Pivotal Tracker user. See
                       https://www.pivotaltracker.com/help/articles/api_token/
  --ctoken CTOKEN      An app token of the Clubhouse user. See
                       https://clubhouse.io/api/v1/#authentication
  --pproject PPROJECT  The Pivotal Tracker project ID from which to transfer
                       stories.
  --cproject CPROJECT  The Clubhouse project ID to which to transfer stories.
```

## API Token Retrieval Instructions
* https://www.pivotaltracker.com/help/articles/api_token/
* https://clubhouse.io/api/v1/#authentication
