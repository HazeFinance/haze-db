# cache
cached off chain data e.g events


## To update the [depositEvents.json.zip](#events/depositEvents.json.zip) (which used in haze ui)
* git clone hazecli repo
* npm install
* node hazecli.js update-past-deposit-events
* commit & push the new depositEvents.json in hazecli to hazecli remote repo
* compress depositEvents.json to depositEvents.json.zip
* copy depositEvents.json.zip to haze-db repo and commit & push
