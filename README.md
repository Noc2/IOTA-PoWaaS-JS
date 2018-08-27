# IOTA-PoWaaS-JS

With this code you can replace the proof of work in iota.lib.js with an API call to https://powsrv.io/

#Usage
```
const IOTA = require("iota.lib.js")
const poWaaS = require("./powaas");
const iota = new IOTA({ provider: "https://nodes.thetangle.org:443" });
poWaaS(iota, "https://api.powsrv.io:443/");

```
