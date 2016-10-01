# viz-client-ibm-hackathon# Symple Client

[![Deploy to Bluemix](https://bluemix.net/deploy/button.png)](https://bluemix.net/deploy?repository=https://github.com/viz-charlie/viz-client-ibm-hackathon)

The Symple JavaScript client is a client-side implementation of the Symple protocol which runs in the web browser. 

Symple is a unrestrictive real time messaging and presence protocol that implements the minimum number of features required to build full fledged messaging applications with security, flexibility, performance and scalability in mind. These features include:

* Session sharing with any backend (via Redis)
* User rostering and presence
* Media streaming (via WebRTC)
* Scoped messaging ie. direct, user and group scope
* Real-time commands and events
* Real-time forms

## Installation

```bash
# install the server
npm install symple

# install the client
npm install symple-client
```


## Usage

The first thing to do is fire up the server:

```bash
cd /path/to/symple/server

node server
```

To use Symple in your app just add the following two scripts into your HTML head, replacing the `src` path with the correct script locations as necessary.


## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

## Contact

For more information please check out the Symple homepage: http://sourcey.com/symple/  
For bugs and issues please use the Github issue tracker: https://github.com/sourcey/symple-client/issues
