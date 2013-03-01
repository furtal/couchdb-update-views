Keep couchdb views up to date
[![Build Status](https://travis-ci.org/nisaacson/couchdb-update-views.png)](https://travis-ci.org/nisaacson/couchdb-update-views)
[![Dependency Status](https://david-dm.org/nisaacson/couchdb-update-views/status.png)](https://david-dm.org/nisaacson/couchdb-update-views/status)
Dependency tracking by [David](http://david-dm.org/)


# Installation
```bash
npm install -g update-couchdb-views
```


# Usage
To update your documents specify the path to a config file and a directory containing your design documents. Both paths can either by relative to your current working directory or full paths to the file on disk
```bash
update-couchdb-views --config ./config.json --docsDir ./docs
```

Update code taken from here
[http://bravenewmethod.wordpress.com/2011/06/03/keeping-couchdb-design-docs-up-to-date-with-node-js/](http://bravenewmethod.wordpress.com/2011/06/03/keeping-couchdb-design-docs-up-to-date-with-node-js/)
