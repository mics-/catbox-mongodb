catbox-mongodb
==============

MongoDB adapter for catbox

[![Build Status](https://secure.travis-ci.org/hapijs/catbox-mongodb.png)](http://travis-ci.org/hapijs/catbox-mongodb)

Lead Maintainer: [Jarda Kotesovec](https://github.com/jardakotesovec)

**catbox-mongodb** serializes values to BSON using MongoDB driver, therefore following data types are supported for this adapter: Object, Array, Number, String, Date, RegExp.


### Options

- `host` - the MongoDB server hostname. Defaults to `'127.0.0.1'`.
- `port` - the MongoDB server port. Defaults to `27017`.
- `username` - when the mongo server requires authentication. Defaults to no authentication.
- `password` - the authentication password when `username` is configured.
- `poolSize` - number of connections. Defaults to `5`.
- `partition` - the MongoDB server database.

