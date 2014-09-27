# node-api-json-docs
Node's API JSON docs in a npm module.

Each package version corresponds to node version the docs were compiled from.

```js
require('node-api-json-docs/crypto.json');
```

```bash
$ npm install node-api-json-docs@<node-version>
$ ls node_modules/node-api-json-docs
addons.json
all.json
assert.json
buffer.json
child_process.json
cluster.json
console.json
crypto.json
debugger.json
dgram.json
dns.json
documentation.json
domain.json
events.json
fs.json
globals.json
http.json
https.json
index.json
modules.json
net.json
os.json
path.json
process.json
punycode.json
querystring.json
readline.json
repl.json
smalloc.json
stream.json
string_decoder.json
synopsis.json
timers.json
tls.json
_toc.json
tracing.json
tty.json
url.json
util.json
vm.json
zlib.json
```

Made with:
```bash
cd node
make doc
cp out/doc/api/*.json ../node-api-json-docs
``
