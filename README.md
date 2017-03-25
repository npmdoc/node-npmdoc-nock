# api documentation for  [nock (v9.0.9)](https://github.com/node-nock/nock#readme)  [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-nock.svg)](https://travis-ci.org/npmdoc/node-npmdoc-nock)
#### HTTP Server mocking for Node.js

[![NPM](https://nodei.co/npm/nock.png?downloads=true)](https://www.npmjs.com/package/nock)

[![apidoc](https://npmdoc.github.io/node-npmdoc-nock/build/screen-capture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-nock_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-nock/build..beta..travis-ci.org/apidoc.html)

![package-listing](https://npmdoc.github.io/node-npmdoc-nock/build/screen-capture.npmPackageListing.svg)



# package.json

```json

{
    "author": {
        "name": "Pedro Teixeira",
        "email": "pedro.teixeira@gmail.com"
    },
    "bugs": {
        "url": "http://github.com/node-nock/nock/issues"
    },
    "contributors": [
        {
            "name": "Bin Chang",
            "url": "https://github.com/BinChang"
        },
        {
            "name": "Roman Hotsiy",
            "url": "https://github.com/RomanGotsiy"
        },
        {
            "name": "Jeffrey Jagoda",
            "url": "https://github.com/jagoda"
        },
        {
            "name": "Hidenari Nozaki",
            "url": "https://github.com/ghiden"
        },
        {
            "name": "Ken Sheedlo",
            "url": "https://github.com/ksheedlo"
        },
        {
            "name": "Douglas Eggleton",
            "url": "https://github.com/douglaseggleton"
        },
        {
            "name": "José F. Romaniello",
            "url": "https://github.com/jfromaniello"
        },
        {
            "name": "Benjamin Urban",
            "url": "https://github.com/benurb"
        },
        {
            "name": "Justin",
            "url": "https://github.com/justincy"
        },
        {
            "name": "Brett Porter"
        },
        {
            "name": "Matt Olson"
        },
        {
            "name": "Rémy HUBSCHER"
        },
        {
            "name": "Roly Fentanes"
        },
        {
            "name": "Alexander Simmerl"
        },
        {
            "name": "Pedro Teixeira"
        },
        {
            "name": "Nuno Job"
        },
        {
            "name": "Ian Young"
        },
        {
            "name": "nilsbunger"
        },
        {
            "name": "bacchusrx",
            "email": "bacchusrx@eightstar.ca"
        },
        {
            "name": "Fabiano França"
        },
        {
            "name": "Sascha Drews"
        },
        {
            "name": "Mike Swift"
        },
        {
            "name": "James Herdman"
        },
        {
            "name": "David Björklund"
        },
        {
            "name": "Andrew Kramolisch"
        },
        {
            "name": "Balazs Nagy"
        },
        {
            "name": "Brian J Brennan"
        },
        {
            "name": "Attila Incze"
        },
        {
            "name": "Mac Angell"
        },
        {
            "name": "Tom Hosford"
        },
        {
            "name": "Aurélien Thieriot"
        },
        {
            "name": "Alex Zylman"
        },
        {
            "name": "Celestino Gomes",
            "email": "contact@tinogomes.com"
        },
        {
            "name": "David Rousselie"
        },
        {
            "name": "spenceralger"
        },
        {
            "name": "Ivan Erceg",
            "email": "ivan@softwaremarbles.com",
            "url": "https://github.com/ierceg"
        },
        {
            "name": "Keith Laban",
            "email": "kelaban17@gmail.com",
            "url": "https://github.com/kelaban"
        },
        {
            "name": "Rui Marinho",
            "email": "ruipmarinho@gmail.com",
            "url": "https://github.com/ruimarinho"
        },
        {
            "name": "David Pate",
            "email": "davidtpate@gmail.com",
            "url": "https://github.com/DavidTPate"
        },
        {
            "name": "Matt Oakes",
            "url": "https://github.com/matto1990"
        },
        {
            "name": "Ian Walker-Sperber",
            "url": "https://github.com/ianwsperber"
        }
    ],
    "dependencies": {
        "chai": ">=1.9.2 <4.0.0",
        "debug": "^2.2.0",
        "deep-equal": "^1.0.0",
        "json-stringify-safe": "^5.0.1",
        "lodash": "~4.17.2",
        "mkdirp": "^0.5.0",
        "propagate": "0.4.0",
        "qs": "^6.0.2"
    },
    "description": "HTTP Server mocking for Node.js",
    "devDependencies": {
        "async": "^2.1.1",
        "aws-sdk": "^2.0.15",
        "browserify": "^13.0.0",
        "changelog": "^1.0.7",
        "coveralls": "^2.11.2",
        "hyperquest": "^1.3.0",
        "isomorphic-fetch": "^2.2.0",
        "istanbul": "^0.4.2",
        "jshint": "^2.5.6",
        "markdown-toc": "^0.13.0",
        "needle": "^1.0.0",
        "node-static": "^0.7.7",
        "nyc": "^10.0.0",
        "pre-commit": "1.1.2",
        "request": "2.71.0",
        "request-promise": "^2.0.1",
        "restify": "^4.0.4",
        "restler": "3.4.0",
        "rimraf": "^2.3.2",
        "superagent": "^3.5.0",
        "tap": "^10.0.0",
        "zombie": "^5.0.1"
    },
    "directories": {},
    "dist": {
        "shasum": "ca4cd923352e206ae3c7d6595cfd7fb223299ec0",
        "tarball": "https://registry.npmjs.org/nock/-/nock-9.0.9.tgz"
    },
    "engines": [
        "node >= 4.0"
    ],
    "gitHead": "5b1a8d8d1196b75729fcfb35cbb7cfe061ae6e47",
    "homepage": "https://github.com/node-nock/nock#readme",
    "license": "MIT",
    "main": "./index",
    "maintainers": [
        {
            "name": "ianwsperber",
            "email": "ianwsperber@gmail.ocm"
        },
        {
            "name": "ierceg",
            "email": "ivan@softwaremarbles.com"
        },
        {
            "name": "pgte",
            "email": "pedro.teixeira@gmail.com"
        },
        {
            "name": "ruimarinho",
            "email": "ruipmarinho@gmail.com"
        },
        {
            "name": "svnlto",
            "email": "me@svenlito.com"
        },
        {
            "name": "vrinek",
            "email": "kostas@vrinek.io"
        }
    ],
    "name": "nock",
    "nyc": {
        "reporter": [
            "lcov",
            "text-summary"
        ],
        "exclude": [
            "tests/test_*.js"
        ]
    },
    "optionalDependencies": {},
    "pre-commit": [
        "jshint",
        "coverage"
    ],
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/node-nock/nock.git"
    },
    "scripts": {
        "changelog": "changelog nock all -m > CHANGELOG.md",
        "coverage": "nyc tap --harmony ./tests/test_*.js",
        "coveralls": "cat ./coverage/lcov.info | coveralls",
        "jshint": "jshint lib/*.js",
        "test": "tap --harmony ./tests/test_*.js",
        "toc": "markdown-toc -i README.md"
    },
    "tags": [
        "Mock",
        "HTTP",
        "testing",
        "isolation"
    ],
    "version": "9.0.9"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module nock](#apidoc.module.nock)
1.  [function <span class="apidocSignatureSpan">nock.</span>activate ()](#apidoc.element.nock.activate)
1.  [function <span class="apidocSignatureSpan">nock.</span>activeMocks ()](#apidoc.element.nock.activeMocks)
1.  [function <span class="apidocSignatureSpan">nock.</span>back (fixtureName, options, nockedFn)](#apidoc.element.nock.back)
1.  [function <span class="apidocSignatureSpan">nock.</span>cleanAll ()](#apidoc.element.nock.cleanAll)
1.  [function <span class="apidocSignatureSpan">nock.</span>define (nockDefs)](#apidoc.element.nock.define)
1.  [function <span class="apidocSignatureSpan">nock.</span>delayed_body (ms, body)](#apidoc.element.nock.delayed_body)
1.  [function <span class="apidocSignatureSpan">nock.</span>disableNetConnect ()](#apidoc.element.nock.disableNetConnect)
1.  [function <span class="apidocSignatureSpan">nock.</span>enableNetConnect (matcher)](#apidoc.element.nock.enableNetConnect)
1.  [function <span class="apidocSignatureSpan">nock.</span>intercept (key, interceptor, scope, scopeOptions, host)](#apidoc.element.nock.intercept)
1.  [function <span class="apidocSignatureSpan">nock.</span>interceptor (scope, uri, method, requestBody, interceptorOptions)](#apidoc.element.nock.interceptor)
1.  [function <span class="apidocSignatureSpan">nock.</span>isActive ()](#apidoc.element.nock.isActive)
1.  [function <span class="apidocSignatureSpan">nock.</span>isDone ()](#apidoc.element.nock.isDone)
1.  [function <span class="apidocSignatureSpan">nock.</span>load (path)](#apidoc.element.nock.load)
1.  [function <span class="apidocSignatureSpan">nock.</span>loadDefs (path)](#apidoc.element.nock.loadDefs)
1.  [function <span class="apidocSignatureSpan">nock.</span>pendingMocks ()](#apidoc.element.nock.pendingMocks)
1.  [function <span class="apidocSignatureSpan">nock.</span>removeInterceptor (options)](#apidoc.element.nock.removeInterceptor)
1.  [function <span class="apidocSignatureSpan">nock.</span>restore ()](#apidoc.element.nock.restore)
1.  [function <span class="apidocSignatureSpan">nock.</span>socket (options)](#apidoc.element.nock.socket)
1.  object <span class="apidocSignatureSpan">nock.</span>common
1.  object <span class="apidocSignatureSpan">nock.</span>delayed_body.prototype
1.  object <span class="apidocSignatureSpan">nock.</span>emitter
1.  object <span class="apidocSignatureSpan">nock.</span>interceptor.prototype
1.  object <span class="apidocSignatureSpan">nock.</span>recorder
1.  object <span class="apidocSignatureSpan">nock.</span>socket.prototype

#### [module nock.back](#apidoc.module.nock.back)
1.  [function <span class="apidocSignatureSpan">nock.</span>back (fixtureName, options, nockedFn)](#apidoc.element.nock.back.back)
1.  [function <span class="apidocSignatureSpan">nock.back.</span>setMode (mode)](#apidoc.element.nock.back.setMode)
1.  object <span class="apidocSignatureSpan">nock.back.</span>fixtures
1.  string <span class="apidocSignatureSpan">nock.back.</span>currentMode

#### [module nock.common](#apidoc.module.nock.common)
1.  [function <span class="apidocSignatureSpan">nock.common.</span>contentEncoding (headers, encoder)](#apidoc.element.nock.common.contentEncoding)
1.  [function <span class="apidocSignatureSpan">nock.common.</span>deleteHeadersField (headers, fieldNameToDelete)](#apidoc.element.nock.common.deleteHeadersField)
1.  [function <span class="apidocSignatureSpan">nock.common.</span>formatQueryValue (key, value, options)](#apidoc.element.nock.common.formatQueryValue)
1.  [function <span class="apidocSignatureSpan">nock.common.</span>headersArrayToObject (rawHeaders)](#apidoc.element.nock.common.headersArrayToObject)
1.  [function <span class="apidocSignatureSpan">nock.common.</span>headersFieldNamesToLowerCase (headers)](#apidoc.element.nock.common.headersFieldNamesToLowerCase)
1.  [function <span class="apidocSignatureSpan">nock.common.</span>headersFieldsArrayToLowerCase (headers)](#apidoc.element.nock.common.headersFieldsArrayToLowerCase)
1.  [function <span class="apidocSignatureSpan">nock.common.</span>isBinaryBuffer (buffer)](#apidoc.element.nock.common.isBinaryBuffer)
1.  [function <span class="apidocSignatureSpan">nock.common.</span>isContentEncoded (headers)](#apidoc.element.nock.common.isContentEncoded)
1.  [function <span class="apidocSignatureSpan">nock.common.</span>isJSONContent (headers)](#apidoc.element.nock.common.isJSONContent)
1.  [function <span class="apidocSignatureSpan">nock.common.</span>isStream (obj)](#apidoc.element.nock.common.isStream)
1.  [function <span class="apidocSignatureSpan">nock.common.</span>matchStringOrRegexp (target, pattern)](#apidoc.element.nock.common.matchStringOrRegexp)
1.  [function <span class="apidocSignatureSpan">nock.common.</span>mergeChunks (chunks)](#apidoc.element.nock.common.mergeChunks)
1.  [function <span class="apidocSignatureSpan">nock.common.</span>normalizeRequestOptions (options)](#apidoc.element.nock.common.normalizeRequestOptions)
1.  [function <span class="apidocSignatureSpan">nock.common.</span>overrideRequests (newRequest)](#apidoc.element.nock.common.overrideRequests)
1.  [function <span class="apidocSignatureSpan">nock.common.</span>percentDecode (str)](#apidoc.element.nock.common.percentDecode)
1.  [function <span class="apidocSignatureSpan">nock.common.</span>percentEncode (str)](#apidoc.element.nock.common.percentEncode)
1.  [function <span class="apidocSignatureSpan">nock.common.</span>restoreOverriddenRequests ()](#apidoc.element.nock.common.restoreOverriddenRequests)
1.  [function <span class="apidocSignatureSpan">nock.common.</span>stringifyRequest (options, body)](#apidoc.element.nock.common.stringifyRequest)

#### [module nock.delayed_body](#apidoc.module.nock.delayed_body)
1.  [function <span class="apidocSignatureSpan">nock.</span>delayed_body (ms, body)](#apidoc.element.nock.delayed_body.delayed_body)
1.  [function <span class="apidocSignatureSpan">nock.delayed_body.</span>super_ (options)](#apidoc.element.nock.delayed_body.super_)

#### [module nock.delayed_body.prototype](#apidoc.module.nock.delayed_body.prototype)
1.  [function <span class="apidocSignatureSpan">nock.delayed_body.prototype.</span>_transform (chunk, encoding, cb)](#apidoc.element.nock.delayed_body.prototype._transform)

#### [module nock.intercept](#apidoc.module.nock.intercept)
1.  [function <span class="apidocSignatureSpan">nock.</span>intercept (key, interceptor, scope, scopeOptions, host)](#apidoc.element.nock.intercept.intercept)
1.  [function <span class="apidocSignatureSpan">nock.intercept.</span>activate ()](#apidoc.element.nock.intercept.activate)
1.  [function <span class="apidocSignatureSpan">nock.intercept.</span>activeMocks ()](#apidoc.element.nock.intercept.activeMocks)
1.  [function <span class="apidocSignatureSpan">nock.intercept.</span>disableNetConnect ()](#apidoc.element.nock.intercept.disableNetConnect)
1.  [function <span class="apidocSignatureSpan">nock.intercept.</span>enableNetConnect (matcher)](#apidoc.element.nock.intercept.enableNetConnect)
1.  [function <span class="apidocSignatureSpan">nock.intercept.</span>isActive ()](#apidoc.element.nock.intercept.isActive)
1.  [function <span class="apidocSignatureSpan">nock.intercept.</span>isDone ()](#apidoc.element.nock.intercept.isDone)
1.  [function <span class="apidocSignatureSpan">nock.intercept.</span>isOn ()](#apidoc.element.nock.intercept.isOn)
1.  [function <span class="apidocSignatureSpan">nock.intercept.</span>overrideClientRequest ()](#apidoc.element.nock.intercept.overrideClientRequest)
1.  [function <span class="apidocSignatureSpan">nock.intercept.</span>pendingMocks ()](#apidoc.element.nock.intercept.pendingMocks)
1.  [function <span class="apidocSignatureSpan">nock.intercept.</span>removeAll ()](#apidoc.element.nock.intercept.removeAll)
1.  [function <span class="apidocSignatureSpan">nock.intercept.</span>removeInterceptor (options)](#apidoc.element.nock.intercept.removeInterceptor)
1.  [function <span class="apidocSignatureSpan">nock.intercept.</span>restoreOverriddenClientRequest ()](#apidoc.element.nock.intercept.restoreOverriddenClientRequest)

#### [module nock.interceptor](#apidoc.module.nock.interceptor)
1.  [function <span class="apidocSignatureSpan">nock.</span>interceptor (scope, uri, method, requestBody, interceptorOptions)](#apidoc.element.nock.interceptor.interceptor)

#### [module nock.interceptor.prototype](#apidoc.module.nock.interceptor.prototype)
1.  [function <span class="apidocSignatureSpan">nock.interceptor.prototype.</span>basicAuth (options)](#apidoc.element.nock.interceptor.prototype.basicAuth)
1.  [function <span class="apidocSignatureSpan">nock.interceptor.prototype.</span>delay (opts)](#apidoc.element.nock.interceptor.prototype.delay)
1.  [function <span class="apidocSignatureSpan">nock.interceptor.prototype.</span>delayBody (ms)](#apidoc.element.nock.interceptor.prototype.delayBody)
1.  [function <span class="apidocSignatureSpan">nock.interceptor.prototype.</span>delayConnection (ms)](#apidoc.element.nock.interceptor.prototype.delayConnection)
1.  [function <span class="apidocSignatureSpan">nock.interceptor.prototype.</span>discard ()](#apidoc.element.nock.interceptor.prototype.discard)
1.  [function <span class="apidocSignatureSpan">nock.interceptor.prototype.</span>filteringPath ()](#apidoc.element.nock.interceptor.prototype.filteringPath)
1.  [function <span class="apidocSignatureSpan">nock.interceptor.prototype.</span>getTotalDelay ()](#apidoc.element.nock.interceptor.prototype.getTotalDelay)
1.  [function <span class="apidocSignatureSpan">nock.interceptor.prototype.</span>match (options, body, hostNameOnly)](#apidoc.element.nock.interceptor.prototype.match)
1.  [function <span class="apidocSignatureSpan">nock.interceptor.prototype.</span>matchHeader (name, value)](#apidoc.element.nock.interceptor.prototype.matchHeader)
1.  [function <span class="apidocSignatureSpan">nock.interceptor.prototype.</span>matchIndependentOfBody (options)](#apidoc.element.nock.interceptor.prototype.matchIndependentOfBody)
1.  [function <span class="apidocSignatureSpan">nock.interceptor.prototype.</span>once ()](#apidoc.element.nock.interceptor.prototype.once)
1.  [function <span class="apidocSignatureSpan">nock.interceptor.prototype.</span>optionally ()](#apidoc.element.nock.interceptor.prototype.optionally)
1.  [function <span class="apidocSignatureSpan">nock.interceptor.prototype.</span>query (queries)](#apidoc.element.nock.interceptor.prototype.query)
1.  [function <span class="apidocSignatureSpan">nock.interceptor.prototype.</span>reply (statusCode, body, rawHeaders)](#apidoc.element.nock.interceptor.prototype.reply)
1.  [function <span class="apidocSignatureSpan">nock.interceptor.prototype.</span>replyWithError (errorMessage)](#apidoc.element.nock.interceptor.prototype.replyWithError)
1.  [function <span class="apidocSignatureSpan">nock.interceptor.prototype.</span>replyWithFile (statusCode, filePath, headers)](#apidoc.element.nock.interceptor.prototype.replyWithFile)
1.  [function <span class="apidocSignatureSpan">nock.interceptor.prototype.</span>reqheaderMatches (options, key)](#apidoc.element.nock.interceptor.prototype.reqheaderMatches)
1.  [function <span class="apidocSignatureSpan">nock.interceptor.prototype.</span>socketDelay (ms)](#apidoc.element.nock.interceptor.prototype.socketDelay)
1.  [function <span class="apidocSignatureSpan">nock.interceptor.prototype.</span>thrice ()](#apidoc.element.nock.interceptor.prototype.thrice)
1.  [function <span class="apidocSignatureSpan">nock.interceptor.prototype.</span>times (newCounter)](#apidoc.element.nock.interceptor.prototype.times)
1.  [function <span class="apidocSignatureSpan">nock.interceptor.prototype.</span>twice ()](#apidoc.element.nock.interceptor.prototype.twice)

#### [module nock.recorder](#apidoc.module.nock.recorder)
1.  [function <span class="apidocSignatureSpan">nock.recorder.</span>clear ()](#apidoc.element.nock.recorder.clear)
1.  [function <span class="apidocSignatureSpan">nock.recorder.</span>play ()](#apidoc.element.nock.recorder.play)
1.  [function <span class="apidocSignatureSpan">nock.recorder.</span>rec (rec_options)](#apidoc.element.nock.recorder.rec)

#### [module nock.socket](#apidoc.module.nock.socket)
1.  [function <span class="apidocSignatureSpan">nock.</span>socket (options)](#apidoc.element.nock.socket.socket)
1.  [function <span class="apidocSignatureSpan">nock.socket.</span>super_ ()](#apidoc.element.nock.socket.super_)

#### [module nock.socket.prototype](#apidoc.module.nock.socket.prototype)
1.  [function <span class="apidocSignatureSpan">nock.socket.prototype.</span>applyDelay (delayMs)](#apidoc.element.nock.socket.prototype.applyDelay)
1.  [function <span class="apidocSignatureSpan">nock.socket.prototype.</span>destroy ()](#apidoc.element.nock.socket.prototype.destroy)
1.  [function <span class="apidocSignatureSpan">nock.socket.prototype.</span>getPeerCertificate ()](#apidoc.element.nock.socket.prototype.getPeerCertificate)
1.  [function <span class="apidocSignatureSpan">nock.socket.prototype.</span>setTimeout (timeoutMs, fn)](#apidoc.element.nock.socket.prototype.setTimeout)



# <a name="apidoc.module.nock"></a>[module nock](#apidoc.module.nock)

#### <a name="apidoc.element.nock.activate"></a>[function <span class="apidocSignatureSpan">nock.</span>activate ()](#apidoc.element.nock.activate)
- description and source-code
```javascript
function activate() {

  if(originalClientRequest) {
    throw new Error('Nock already active');
  }

  overrideClientRequest();

  // ----- Overriding http.request and https.request:

  common.overrideRequests(function(proto, overriddenRequest, options, callback) {
    //  NOTE: overriddenRequest is already bound to its module.
    var req,
        res;

    if (typeof options === 'string') {
      options = parse(options);
    }
    options.proto = proto;

    var interceptors = interceptorsFor(options)

    if (isOn() && interceptors) {
      var matches = false,
          allowUnmocked = false;

      matches = !! _.find(interceptors, function(interceptor) {
        return interceptor.matchIndependentOfBody(options);
      });

      allowUnmocked = !! _.find(interceptors, function(interceptor) {
        return interceptor.options.allowUnmocked;
      });

      if (! matches && allowUnmocked) {
        if (proto === 'https') {
          var ClientRequest = http.ClientRequest;
          http.ClientRequest = originalClientRequest;
          req = overriddenRequest(options, callback);
          http.ClientRequest = ClientRequest;
        } else {
          req = overriddenRequest(options, callback);
        }
        globalEmitter.emit('no match', req);
        return req;
      }

      //  NOTE: Since we already overrode the http.ClientRequest we are in fact constructing
      //    our own OverriddenClientRequest.
      req = new http.ClientRequest(options);

      res = RequestOverrider(req, options, interceptors, remove);
      if (callback) {
        res.on('response', callback);
      }
      return req;
    } else {
      globalEmitter.emit('no match', options);
      if (isOff() || isEnabledForNetConnect(options)) {
        return overriddenRequest(options, callback);
      } else {
        var error = new NetConnectNotAllowedError(options.host, options.path);
        return new ErroringClientRequest(error);
      }
    }
  });

}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.nock.activeMocks"></a>[function <span class="apidocSignatureSpan">nock.</span>activeMocks ()](#apidoc.element.nock.activeMocks)
- description and source-code
```javascript
function activeMocks() {
  return _.flatten(_.map(interceptorScopes(), function(scope) {
    return scope.activeMocks();
  }));
}
```
- example usage
```shell
...
* [Optional Requests](#optional-requests)
* [Allow __unmocked__ requests on a mocked hostname](#allow-__unmocked__-requests-on-a-mocked-hostname)
- [Expectations](#expectations)
* [.isDone()](#isdone)
* [.cleanAll()](#cleanall)
* [.persist()](#persist)
* [.pendingMocks()](#pendingmocks)
* [.activeMocks()](#activemocks)
- [Logging](#logging)
- [Restoring](#restoring)
- [Turning Nock Off (experimental!)](#turning-nock-off-experimental)
- [Enable/Disable real HTTP request](#enabledisable-real-http-request)
- [Recording](#recording)
* ['dont_print' option](#dont_print-option)
* ['output_objects' option](#output_objects-option)
...
```

#### <a name="apidoc.element.nock.back"></a>[function <span class="apidocSignatureSpan">nock.</span>back (fixtureName, options, nockedFn)](#apidoc.element.nock.back)
- description and source-code
```javascript
function Back(fixtureName, options, nockedFn) {
  if(!Back.fixtures) {
    throw new Error(  'Back requires nock.back.fixtures to be set\n' +
                      'Ex:\n' +
                      '\trequire(nock).back.fixtures = \'/path/to/fixures/\'');
  }

  if( arguments.length === 2 ) {
    nockedFn = options;
    options = {};
  }

  _mode.setup();

  var fixture = path.join(Back.fixtures, fixtureName)
    , context = _mode.start(fixture, options);


  var nockDone = function () {
    _mode.finish(fixture, options, context);
  };

  debug('context:', context);

  nockedFn.call(context, nockDone);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.nock.cleanAll"></a>[function <span class="apidocSignatureSpan">nock.</span>cleanAll ()](#apidoc.element.nock.cleanAll)
- description and source-code
```javascript
function cleanAll() {
  globalIntercept.removeAll();
  return module.exports;
}
```
- example usage
```shell
...
  * [Path filtering](#path-filtering)
  * [Request Body filtering](#request-body-filtering)
  * [Request Headers Matching](#request-headers-matching)
  * [Optional Requests](#optional-requests)
  * [Allow __unmocked__ requests on a mocked hostname](#allow-__unmocked__-requests-on-a-mocked-hostname)
- [Expectations](#expectations)
  * [.isDone()](#isdone)
  * [.cleanAll()](#cleanall)
  * [.persist()](#persist)
  * [.pendingMocks()](#pendingmocks)
  * [.activeMocks()](#activemocks)
- [Logging](#logging)
- [Restoring](#restoring)
- [Turning Nock Off (experimental!)](#turning-nock-off-experimental)
- [Enable/Disable real HTTP request](#enabledisable-real-http-request)
...
```

#### <a name="apidoc.element.nock.define"></a>[function <span class="apidocSignatureSpan">nock.</span>define (nockDefs)](#apidoc.element.nock.define)
- description and source-code
```javascript
function define(nockDefs) {

  var nocks     = [];

  nockDefs.forEach(function(nockDef) {

    var nscope     = getScopeFromDefinition(nockDef)
      , npath      = nockDef.path
      , method     = nockDef.method.toLowerCase() || "get"
      , status     = getStatusFromDefinition(nockDef)
      , rawHeaders = nockDef.rawHeaders || []
      , reqheaders = nockDef.reqheaders || {}
      , body       = nockDef.body       || ''
      , options    = nockDef.options    || {};

    //  We use request headers for both filtering (see below) and mocking.
    //  Here we are setting up mocked request headers but we don't want to
    //  be changing the user's options object so we clone it first.
    options = _.clone(options) || {};
    options.reqheaders = reqheaders;

    //  Response is not always JSON as it could be a string or binary data or
    //  even an array of binary buffers (e.g. when content is enconded)
    var response;
    if (!nockDef.response) {
      response = '';
    } else {
      response = _.isString(nockDef.response) ? tryJsonParse(nockDef.response) : nockDef.response;
    }

    var nock;
    if (body==="*") {
      nock = startScope(nscope, options).filteringRequestBody(function() {
        return "*";
      })[method](npath, "*").reply(status, response, rawHeaders);
    } else {
      nock = startScope(nscope, options);
      //  If request headers were specified filter by them.
      if (_.size(reqheaders) > 0) {
        for (var k in reqheaders) {
          nock.matchHeader(k, reqheaders[k]);
        }
      }
      if (nockDef.filteringRequestBody) {
        nock.filteringRequestBody(nockDef.filteringRequestBody);
      }
      nock.intercept(npath, method, body).reply(status, response, rawHeaders);
    }

    nocks.push(nock);

  });

  return nocks;
}
```
- example usage
```shell
...
  return body.replace(/(timestamp):([0-9]+)/g, function(match, key, value) {
    return key + ':' + recordedTimestamp;
  });
};
});
'''

Alternatively, if you need to pre-process the captured nock definitions before using them (e.g. to add scope filtering) then you
 can use 'nock.loadDefs(path)' and 'nock.define(nockDefs)'. Shown here is scope filtering for Dropbox node module which constantly
 changes the subdomain to which it sends the requests:

'''js
//  Pre-process the nock definitions as scope filtering has to be defined before the nocks are defined (due to its very hacky nature
).
var nockDefs = nock.loadDefs(pathToJson);
nockDefs.forEach(function(def) {
//  Do something with the definition object e.g. scope filtering.
def.options = def.options || {};
...
```

#### <a name="apidoc.element.nock.delayed_body"></a>[function <span class="apidocSignatureSpan">nock.</span>delayed_body (ms, body)](#apidoc.element.nock.delayed_body)
- description and source-code
```javascript
function DelayedBody(ms, body) {
  Transform.call(this);

  var self = this;
  var data = '';
  var ended = false;

  if (common.isStream(body)) {
    body.on('data', function (chunk) {
      data += Buffer.isBuffer(chunk) ? chunk.toString() : chunk;
    });

    body.once('end', function () {
      ended = true;
    });

    body.resume();
  }

  setTimeout(function () {
    if (common.isStream(body) && !ended) {
      body.once('end', function () {
        self.end(data);
      });
    } else {
      self.end(data || body);
    }
  }, ms);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.nock.disableNetConnect"></a>[function <span class="apidocSignatureSpan">nock.</span>disableNetConnect ()](#apidoc.element.nock.disableNetConnect)
- description and source-code
```javascript
function disableNetConnect() {
  allowNetConnect = undefined;
}
```
- example usage
```shell
...
# Enable/Disable real HTTP request

As default, if you do not mock a host, a real HTTP request will do, but sometimes you should not permit real HTTP request, so...

For disabling real http requests.

'''js
nock.disableNetConnect();
'''

So, if you try to request any host not 'nocked', it will thrown an 'NetConnectNotAllowedError'.

'''js
nock.disableNetConnect();
var req = http.get('http://google.com/');
...
```

#### <a name="apidoc.element.nock.enableNetConnect"></a>[function <span class="apidocSignatureSpan">nock.</span>enableNetConnect (matcher)](#apidoc.element.nock.enableNetConnect)
- description and source-code
```javascript
function enableNetConnect(matcher) {
  if (_.isString(matcher)) {
    allowNetConnect = new RegExp(matcher);
  } else if (_.isObject(matcher) && _.isFunction(matcher.test)) {
    allowNetConnect = matcher;
  } else {
    allowNetConnect = /.*/;
  }
}
```
- example usage
```shell
...
// This code will log a NetConnectNotAllowedError with message:
// Nock: Not allow net connect for "google.com:80"
'''

For enabling real HTTP requests (the default behaviour).

'''js
nock.enableNetConnect();
'''

You could allow real HTTP request for certain host names by providing a string or a regular expression for the hostname:

'''js
// using a string
nock.enableNetConnect('amazon.com');
...
```

#### <a name="apidoc.element.nock.intercept"></a>[function <span class="apidocSignatureSpan">nock.</span>intercept (key, interceptor, scope, scopeOptions, host)](#apidoc.element.nock.intercept)
- description and source-code
```javascript
function add(key, interceptor, scope, scopeOptions, host) {
  if (! allInterceptors.hasOwnProperty(key)) {
    allInterceptors[key] = { key: key, scopes: [] };
  }
  interceptor.__nock_scope = scope;

  //  We need scope's key and scope options for scope filtering function (if defined)
  interceptor.__nock_scopeKey = key;
  interceptor.__nock_scopeOptions = scopeOptions;
  //  We need scope's host for setting correct request headers for filtered scopes.
  interceptor.__nock_scopeHost = host;
  interceptor.interceptionCounter = 0;

  allInterceptors[key].scopes.push(interceptor);
}
```
- example usage
```shell
...
  .reply(200, { hello: 'world' });
'''

## HTTP Verbs

Nock supports any HTTP verb, and it has convenience methods for the GET, POST, PUT, HEAD, DELETE, PATCH and MERGE HTTP verbs.

You can intercept any HTTP verb using '.intercept(path, verb [, requestBody [, options]])':

'''js
scope('http://my.domain.com')
  .intercept('/path', 'PATCH')
  .reply(304);
'''
...
```

#### <a name="apidoc.element.nock.interceptor"></a>[function <span class="apidocSignatureSpan">nock.</span>interceptor (scope, uri, method, requestBody, interceptorOptions)](#apidoc.element.nock.interceptor)
- description and source-code
```javascript
function Interceptor(scope, uri, method, requestBody, interceptorOptions) {
    this.scope = scope;
    this.interceptorMatchHeaders = [];
    this.method = method.toUpperCase();
    this.uri = uri;
    this._key = this.method + ' ' + scope.basePath + scope.basePathname + (typeof uri === 'string' ? '' : '/') + uri;
    this.basePath = this.scope.basePath;
    this.path = (typeof uri === 'string') ? scope.basePathname + uri : uri;

    this.baseUri = this.method + ' ' + scope.basePath + scope.basePathname;
    this.options = interceptorOptions || {};
    this.counter = 1;
    this._requestBody = requestBody;

    //  We use lower-case header field names throughout Nock.
    this.reqheaders = common.headersFieldNamesToLowerCase((scope.scopeOptions && scope.scopeOptions.reqheaders) || {});
    this.badheaders = common.headersFieldsArrayToLowerCase((scope.scopeOptions && scope.scopeOptions.badheaders) || []);


    this.delayInMs = 0;
    this.delayConnectionInMs = 0;

    this.optional = false;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.nock.isActive"></a>[function <span class="apidocSignatureSpan">nock.</span>isActive ()](#apidoc.element.nock.isActive)
- description and source-code
```javascript
function isActive() {

  //  If ClientRequest has been overwritten by Nock then originalClientRequest is not undefined.
  //  This means that Nock has been activated.
  return !_.isUndefined(originalClientRequest);

}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.nock.isDone"></a>[function <span class="apidocSignatureSpan">nock.</span>isDone ()](#apidoc.element.nock.isDone)
- description and source-code
```javascript
function isDone() {
  return _.every(interceptorScopes(), function(scope) {
    return scope.isDone();
  });
}
```
- example usage
```shell
...
  * [Scope filtering](#scope-filtering)
  * [Path filtering](#path-filtering)
  * [Request Body filtering](#request-body-filtering)
  * [Request Headers Matching](#request-headers-matching)
  * [Optional Requests](#optional-requests)
  * [Allow __unmocked__ requests on a mocked hostname](#allow-__unmocked__-requests-on-a-mocked-hostname)
- [Expectations](#expectations)
  * [.isDone()](#isdone)
  * [.cleanAll()](#cleanall)
  * [.persist()](#persist)
  * [.pendingMocks()](#pendingmocks)
  * [.activeMocks()](#activemocks)
- [Logging](#logging)
- [Restoring](#restoring)
- [Turning Nock Off (experimental!)](#turning-nock-off-experimental)
...
```

#### <a name="apidoc.element.nock.load"></a>[function <span class="apidocSignatureSpan">nock.</span>load (path)](#apidoc.element.nock.load)
- description and source-code
```javascript
function load(path) {
  return define(loadDefs(path));
}
```
- example usage
```shell
...
* 'path' - the path of the call (e.g. ''/pgte/nock'')
* 'body' - the body of the call, if any
* 'status' - the HTTP status of the reply (e.g. '200')
* 'response' - the body of the reply which can be a JSON, string, hex string representing binary buffers or an array of such hex
 strings (when handling 'content-encoded' in reply header)
* 'headers' - the headers of the reply
* 'reqheader' - the headers of the request

If you save this as a JSON file, you can load them directly through 'nock.load(path)'. Then you can post-process them before using
 them in the tests for example to add them request body filtering (shown here fixing timestamps to match the ones captured during
 recording):

'''js
nocks = nock.load(pathToJson);
nocks.forEach(function(nock) {
nock.filteringRequestBody = function(body, aRecordedBody) {
  if (typeof(body) !== 'string' || typeof(aRecordedBody) !== 'string') {
    return body;
...
```

#### <a name="apidoc.element.nock.loadDefs"></a>[function <span class="apidocSignatureSpan">nock.</span>loadDefs (path)](#apidoc.element.nock.loadDefs)
- description and source-code
```javascript
function loadDefs(path) {
  if (! fs) {
    throw new Error('No fs');
  }

  var contents = fs.readFileSync(path);
  return JSON.parse(contents);
}
```
- example usage
```shell
...
  return body.replace(/(timestamp):([0-9]+)/g, function(match, key, value) {
    return key + ':' + recordedTimestamp;
  });
};
});
'''

Alternatively, if you need to pre-process the captured nock definitions before using them (e.g. to add scope filtering) then you
 can use 'nock.loadDefs(path)' and 'nock.define(nockDefs)'. Shown here is scope filtering for Dropbox node module which constantly
 changes the subdomain to which it sends the requests:

'''js
//  Pre-process the nock definitions as scope filtering has to be defined before the nocks are defined (due to its very hacky nature
).
var nockDefs = nock.loadDefs(pathToJson);
nockDefs.forEach(function(def) {
//  Do something with the definition object e.g. scope filtering.
def.options = def.options || {};
...
```

#### <a name="apidoc.element.nock.pendingMocks"></a>[function <span class="apidocSignatureSpan">nock.</span>pendingMocks ()](#apidoc.element.nock.pendingMocks)
- description and source-code
```javascript
function pendingMocks() {
  return _.flatten(_.map(interceptorScopes(), function(scope) {
    return scope.pendingMocks();
  }));
}
```
- example usage
```shell
...
* [Request Headers Matching](#request-headers-matching)
* [Optional Requests](#optional-requests)
* [Allow __unmocked__ requests on a mocked hostname](#allow-__unmocked__-requests-on-a-mocked-hostname)
- [Expectations](#expectations)
* [.isDone()](#isdone)
* [.cleanAll()](#cleanall)
* [.persist()](#persist)
* [.pendingMocks()](#pendingmocks)
* [.activeMocks()](#activemocks)
- [Logging](#logging)
- [Restoring](#restoring)
- [Turning Nock Off (experimental!)](#turning-nock-off-experimental)
- [Enable/Disable real HTTP request](#enabledisable-real-http-request)
- [Recording](#recording)
* ['dont_print' option](#dont_print-option)
...
```

#### <a name="apidoc.element.nock.removeInterceptor"></a>[function <span class="apidocSignatureSpan">nock.</span>removeInterceptor (options)](#apidoc.element.nock.removeInterceptor)
- description and source-code
```javascript
function removeInterceptor(options) {
  var baseUrl, key, method, proto;
  if (options instanceof Interceptor) {
    baseUrl = options.basePath;
    key = options._key;
  } else {
    proto = options.proto ? options.proto : 'http';

    common.normalizeRequestOptions(options);
    baseUrl = proto + '://' + options.host;
    method = options.method && options.method.toUpperCase() || 'GET';
    key = method + ' ' + baseUrl + (options.path || '/');
  }

  if (allInterceptors[baseUrl] && allInterceptors[baseUrl].scopes.length > 0) {
    if (key) {
      for (var i = 0; i < allInterceptors[baseUrl].scopes.length; i++) {
        var interceptor = allInterceptors[baseUrl].scopes[i];
        if (interceptor._key === key) {
          allInterceptors[baseUrl].scopes.splice(i, 1);
          interceptor.scope.remove(key, interceptor);
          break;
        }
      }
    } else {
      allInterceptors[baseUrl].scopes.length = 0;
    }

    return true;
  }

  return false;
}
```
- example usage
```shell
...
- [Enable/Disable real HTTP request](#enabledisable-real-http-request)
- [Recording](#recording)
* ['dont_print' option](#dont_print-option)
* ['output_objects' option](#output_objects-option)
* ['enable_reqheaders_recording' option](#enable_reqheaders_recording-option)
* ['logging' option](#logging-option)
* ['use_separator' option](#use_separator-option)
* [.removeInterceptor()](#removeinterceptor)
- [Events](#events)
* [Global no match event](#global-no-match-event)
- [Nock Back](#nock-back)
* [Setup](#setup)
  + [Options](#options)
* [Usage](#usage)
  + [Options](#options-1)
...
```

#### <a name="apidoc.element.nock.restore"></a>[function <span class="apidocSignatureSpan">nock.</span>restore ()](#apidoc.element.nock.restore)
- description and source-code
```javascript
function restore() {
  debug(currentRecordingId, 'restoring all the overridden http/https properties');

  common.restoreOverriddenRequests();
  intercept.restoreOverriddenClientRequest();
  recordingInProgress = false;
}
```
- example usage
```shell
...
'''

# Restoring

You can restore the HTTP interceptor to the normal unmocked behaviour by calling:

'''js
nock.restore();
'''
**note**: restore does not clear the interceptor list. Use [nock.cleanAll()](#cleanall) if you expect the interceptor list to be
 empty.

# Turning Nock Off (experimental!)

You can bypass Nock completely by setting 'NOCK_OFF' environment variable to '"true"'.
...
```

#### <a name="apidoc.element.nock.socket"></a>[function <span class="apidocSignatureSpan">nock.</span>socket (options)](#apidoc.element.nock.socket)
- description and source-code
```javascript
function Socket(options) {
  if (!(this instanceof Socket)) {
    return new Socket(options);
  }

  EventEmitter.apply(this);

  options = options || {};

  if (options.proto === 'https') {
    this.authorized = true;
  }

  this.writable = true;
  this.readable = true;
  this.destroyed = false;

  this.setNoDelay = noop;
  this.setKeepAlive = noop;
  this.resume = noop;

  // totalDelay that has already been applied to the current
  // request/connection, timeout error will be generated if
  // it is timed-out.
  this.totalDelayMs = 0;
  // Maximum allowed delay. Null means unlimited.
  this.timeoutMs = null;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.nock.back"></a>[module nock.back](#apidoc.module.nock.back)

#### <a name="apidoc.element.nock.back.back"></a>[function <span class="apidocSignatureSpan">nock.</span>back (fixtureName, options, nockedFn)](#apidoc.element.nock.back.back)
- description and source-code
```javascript
function Back(fixtureName, options, nockedFn) {
  if(!Back.fixtures) {
    throw new Error(  'Back requires nock.back.fixtures to be set\n' +
                      'Ex:\n' +
                      '\trequire(nock).back.fixtures = \'/path/to/fixures/\'');
  }

  if( arguments.length === 2 ) {
    nockedFn = options;
    options = {};
  }

  _mode.setup();

  var fixture = path.join(Back.fixtures, fixtureName)
    , context = _mode.start(fixture, options);


  var nockDone = function () {
    _mode.finish(fixture, options, context);
  };

  debug('context:', context);

  nockedFn.call(context, nockDone);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.nock.back.setMode"></a>[function <span class="apidocSignatureSpan">nock.back.</span>setMode (mode)](#apidoc.element.nock.back.setMode)
- description and source-code
```javascript
setMode = function (mode) {
  if( !Modes.hasOwnProperty(mode) ) {
    throw new Error ('some usage error');
  }

  Back.currentMode = mode;
  debug('New nock back mode:', Back.currentMode);

  _mode = Modes[mode];
  _mode.setup();
}
```
- example usage
```shell
...

In your test helper

'''javascript
var nockBack = require('nock').back;

nockBack.fixtures = '/path/to/fixtures/';
nockBack.setMode('record');
'''

### Options

- 'nockBack.fixtures' : path to fixture directory
- 'nockBack.setMode()' : the mode to use
...
```



# <a name="apidoc.module.nock.common"></a>[module nock.common](#apidoc.module.nock.common)

#### <a name="apidoc.element.nock.common.contentEncoding"></a>[function <span class="apidocSignatureSpan">nock.common.</span>contentEncoding (headers, encoder)](#apidoc.element.nock.common.contentEncoding)
- description and source-code
```javascript
function contentEncoding(headers, encoder) {
  var contentEncoding = _.get(headers, 'content-encoding');
  return contentEncoding === encoder;
}
```
- example usage
```shell
...
response.headers = _.extend({}, interceptor.headers);
response.rawHeaders = (interceptor.rawHeaders || []).slice();
debug('response.rawHeaders:', response.rawHeaders);


if (typeof interceptor.body === 'function') {
  if (requestBody && common.isJSONContent(options.headers)) {
    if (requestBody && common.contentEncoding(options.headers, 'gzip')) {
      if (typeof zlib.gunzipSync !== 'function') {
        emitError(new Error('Gzip encoding is currently not supported in this version of Node.'));
        return;
      }
      requestBody = String(zlib.gunzipSync(new Buffer(requestBody, 'hex')), 'hex')
    } else if (requestBody && common.contentEncoding(options.headers, 'deflate')) {
      if (typeof zlib.deflateSync !== 'function') {
...
```

#### <a name="apidoc.element.nock.common.deleteHeadersField"></a>[function <span class="apidocSignatureSpan">nock.common.</span>deleteHeadersField (headers, fieldNameToDelete)](#apidoc.element.nock.common.deleteHeadersField)
- description and source-code
```javascript
deleteHeadersField = function (headers, fieldNameToDelete) {

  if(!_.isObject(headers) || !_.isString(fieldNameToDelete)) {
    return;
  }

  var lowerCaseFieldNameToDelete = fieldNameToDelete.toLowerCase();

  //  Search through the headers and delete all values whose field name matches the given field name.
  _(headers).keys().each(function(fieldName) {
    var lowerCaseFieldName = fieldName.toLowerCase();
    if(lowerCaseFieldName === lowerCaseFieldNameToDelete) {
      delete headers[fieldName];
      //  We don't stop here but continue in order to remove *all* matching field names
      //  (even though if seen regorously there shouldn't be any)
    }
  });

}
```
- example usage
```shell
...

var out;
if(output_objects) {
  out = generateRequestAndResponseObject(req, bodyChunks, options, res, dataChunks);
  if(out.reqheaders) {
    //  We never record user-agent headers as they are worse than useless -
    //  they actually make testing more difficult without providing any benefit (see README)
    common.deleteHeadersField(out.reqheaders, 'user-agent');

    //  Remove request headers completely unless it was explicitly enabled by the user (see README)
    if(!enable_reqheaders_recording) {
      delete out.reqheaders;
    }
  }
} else {
...
```

#### <a name="apidoc.element.nock.common.formatQueryValue"></a>[function <span class="apidocSignatureSpan">nock.common.</span>formatQueryValue (key, value, options)](#apidoc.element.nock.common.formatQueryValue)
- description and source-code
```javascript
function formatQueryValue(key, value, options) {
  switch (true) {
    case _.isNumber(value): // fall-though
    case _.isBoolean(value):
      value = value.toString();
      break;
    case _.isUndefined(value): // fall-though
    case _.isNull(value):
      value = '';
      break;
    case _.isString(value):
      if(options.encodedQueryParams) {
        value = percentDecode(value);
      }
      break;
    case (value instanceof RegExp):
      break;
    case _.isArray(value):
      var tmpArray = new Array(value.length);
      for (var i = 0; i < value.length; ++i) {
        tmpArray[i] = formatQueryValue(i, value[i], options)[1];
      }
      value = tmpArray;
      break;
    case _.isObject(value):
      var tmpObj = {};
      _.forOwn(value, function(subVal, subKey){
        var subPair = formatQueryValue(subKey, subVal, options);
        tmpObj[subPair[0]] = subPair[1];
      });
      value = tmpObj;
      break;
  }

  if (options.encodedQueryParams) key = percentDecode(key);
  return [key, value];
}
```
- example usage
```shell
...
        this.queries = queries;
        return this;
    }

    for (var q in queries) {
        if (_.isUndefined(this.queries[q])) {
            var value = queries[q];
            var formatedPair = common.formatQueryValue(q, value, this.scope.scopeOptions);
            this.queries[formatedPair[0]] = formatedPair[1];
        }
    }

    return this;
};
...
```

#### <a name="apidoc.element.nock.common.headersArrayToObject"></a>[function <span class="apidocSignatureSpan">nock.common.</span>headersArrayToObject (rawHeaders)](#apidoc.element.nock.common.headersArrayToObject)
- description and source-code
```javascript
headersArrayToObject = function (rawHeaders) {
  if(!_.isArray(rawHeaders)) {
    return rawHeaders;
  }

  var headers = {};

  for (var i=0, len=rawHeaders.length; i<len; i=i+2) {
    var key = rawHeaders[i];
    var value = rawHeaders[i+1];

    if (headers[key]) {
      headers[key] = _.isArray(headers[key]) ? headers[key] : [headers[key]];
      headers[key].push(value);
    } else {
      headers[key] = value;
    }
  }

  return headers;
}
```
- example usage
```shell
...
}

this.statusCode = statusCode;

_.defaults(this.options, this.scope.scopeOptions);

// convert rawHeaders from Array to Object
var headers = common.headersArrayToObject(rawHeaders);

if (this.scope._defaultReplyHeaders) {
    headers = headers || {};
    headers = mixin(this.scope._defaultReplyHeaders, headers);
}

if (this.scope.date) {
...
```

#### <a name="apidoc.element.nock.common.headersFieldNamesToLowerCase"></a>[function <span class="apidocSignatureSpan">nock.common.</span>headersFieldNamesToLowerCase (headers)](#apidoc.element.nock.common.headersFieldNamesToLowerCase)
- description and source-code
```javascript
headersFieldNamesToLowerCase = function (headers) {
  if(!_.isObject(headers)) {
    return headers;
  }

  //  For each key in the headers, delete its value and reinsert it with lower-case key.
  //  Keys represent headers field names.
  var lowerCaseHeaders = {};
  _.forOwn(headers, function(fieldVal, fieldName) {
    var lowerCaseFieldName = fieldName.toLowerCase();
    if(!_.isUndefined(lowerCaseHeaders[lowerCaseFieldName])) {
      throw new Error('Failed to convert header keys to lower case due to field name conflict: ' + lowerCaseFieldName);
    }
    lowerCaseHeaders[lowerCaseFieldName] = fieldVal;
  });

  return lowerCaseHeaders;
}
```
- example usage
```shell
...

this.baseUri = this.method + ' ' + scope.basePath + scope.basePathname;
this.options = interceptorOptions || {};
this.counter = 1;
this._requestBody = requestBody;

//  We use lower-case header field names throughout Nock.
this.reqheaders = common.headersFieldNamesToLowerCase((scope.scopeOptions && scope.scopeOptions.reqheaders) || {});
this.badheaders = common.headersFieldsArrayToLowerCase((scope.scopeOptions && scope.scopeOptions.badheaders) || []);


this.delayInMs = 0;
this.delayConnectionInMs = 0;

this.optional = false;
...
```

#### <a name="apidoc.element.nock.common.headersFieldsArrayToLowerCase"></a>[function <span class="apidocSignatureSpan">nock.common.</span>headersFieldsArrayToLowerCase (headers)](#apidoc.element.nock.common.headersFieldsArrayToLowerCase)
- description and source-code
```javascript
headersFieldsArrayToLowerCase = function (headers) {
  return _.uniq(_.map(headers, function (fieldName) {
    return fieldName.toLowerCase();
  }));
}
```
- example usage
```shell
...
    this.baseUri = this.method + ' ' + scope.basePath + scope.basePathname;
    this.options = interceptorOptions || {};
    this.counter = 1;
    this._requestBody = requestBody;

    //  We use lower-case header field names throughout Nock.
    this.reqheaders = common.headersFieldNamesToLowerCase((scope.scopeOptions && scope.scopeOptions.reqheaders) || {});
    this.badheaders = common.headersFieldsArrayToLowerCase((scope.scopeOptions && scope.scopeOptions.badheaders) || []);


    this.delayInMs = 0;
    this.delayConnectionInMs = 0;

    this.optional = false;
}
...
```

#### <a name="apidoc.element.nock.common.isBinaryBuffer"></a>[function <span class="apidocSignatureSpan">nock.common.</span>isBinaryBuffer (buffer)](#apidoc.element.nock.common.isBinaryBuffer)
- description and source-code
```javascript
isBinaryBuffer = function (buffer) {

  if(!Buffer.isBuffer(buffer)) {
    return false;
  }

  //  Test if the buffer can be reconstructed verbatim from its utf8 encoding.
  var utfEncodedBuffer = buffer.toString('utf8');
  var reconstructedBuffer = new Buffer(utfEncodedBuffer, 'utf8');
  var compareBuffers = function(lhs, rhs) {
    if(lhs.length !== rhs.length) {
      return false;
    }

    for(var i = 0; i < lhs.length; ++i) {
      if(lhs[i] !== rhs[i]) {
        return false;
      }
    }

    return true;
  };

  //  If the buffers are *not* equal then this is a "binary buffer"
  //  meaning that it cannot be faitfully represented in utf8.
  return !compareBuffers(buffer, reconstructedBuffer);

}
```
- example usage
```shell
...
var mergedBuffer = common.mergeChunks(chunks);

//  The merged buffer can be one of three things:
//    1.  A binary buffer which then has to be recorded as a hex string.
//    2.  A string buffer which represents a JSON object.
//    3.  A string buffer which doesn't represent a JSON object.

if(common.isBinaryBuffer(mergedBuffer)) {
  return mergedBuffer.toString('hex');
} else {
  var maybeStringifiedJson = mergedBuffer.toString('utf8');
  try {
    return JSON.parse(maybeStringifiedJson);
  } catch(err) {
    return maybeStringifiedJson;
...
```

#### <a name="apidoc.element.nock.common.isContentEncoded"></a>[function <span class="apidocSignatureSpan">nock.common.</span>isContentEncoded (headers)](#apidoc.element.nock.common.isContentEncoded)
- description and source-code
```javascript
function isContentEncoded(headers) {
  var contentEncoding = _.get(headers, 'content-encoding');
  return _.isString(contentEncoding) && contentEncoding !== '';
}
```
- example usage
```shell
...

    debug('reply.headers:', this.headers);
    debug('reply.rawHeaders:', this.rawHeaders);
}

//  If the content is not encoded we may need to transform the response body.
//  Otherwise we leave it as it is.
if (!common.isContentEncoded(this.headers)) {
    if (body && typeof(body) !== 'string' &&
        typeof(body) !== 'function' &&
        !Buffer.isBuffer(body) &&
        !common.isStream(body)) {
        try {
            body = stringify(body);
            if (!this.headers) {
...
```

#### <a name="apidoc.element.nock.common.isJSONContent"></a>[function <span class="apidocSignatureSpan">nock.common.</span>isJSONContent (headers)](#apidoc.element.nock.common.isJSONContent)
- description and source-code
```javascript
function isJSONContent(headers) {
  var contentType = _.get(headers, 'content-type');
  if (Array.isArray(contentType)) {
    contentType = contentType[0];
  }
  contentType = (contentType || '').toLocaleLowerCase();

  return contentType === 'application/json';
}
```
- example usage
```shell
...
// Clone headers/rawHeaders to not override them when evaluating later
response.headers = _.extend({}, interceptor.headers);
response.rawHeaders = (interceptor.rawHeaders || []).slice();
debug('response.rawHeaders:', response.rawHeaders);


if (typeof interceptor.body === 'function') {
  if (requestBody && common.isJSONContent(options.headers)) {
    if (requestBody && common.contentEncoding(options.headers, 'gzip')) {
      if (typeof zlib.gunzipSync !== 'function') {
        emitError(new Error('Gzip encoding is currently not supported in this version of Node.'));
        return;
      }
      requestBody = String(zlib.gunzipSync(new Buffer(requestBody, 'hex')), 'hex')
    } else if (requestBody && common.contentEncoding(options.headers, 'deflate')) {
...
```

#### <a name="apidoc.element.nock.common.isStream"></a>[function <span class="apidocSignatureSpan">nock.common.</span>isStream (obj)](#apidoc.element.nock.common.isStream)
- description and source-code
```javascript
function isStream(obj) {
  return obj &&
      (typeof a !== 'string') &&
      (! Buffer.isBuffer(obj)) &&
      _.isFunction(obj.setEncoding);
}
```
- example usage
```shell
...
function DelayedBody(ms, body) {
  Transform.call(this);

  var self = this;
  var data = '';
  var ended = false;

  if (common.isStream(body)) {
body.on('data', function (chunk) {
  data += Buffer.isBuffer(chunk) ? chunk.toString() : chunk;
});

body.once('end', function () {
  ended = true;
});
...
```

#### <a name="apidoc.element.nock.common.matchStringOrRegexp"></a>[function <span class="apidocSignatureSpan">nock.common.</span>matchStringOrRegexp (target, pattern)](#apidoc.element.nock.common.matchStringOrRegexp)
- description and source-code
```javascript
function matchStringOrRegexp(target, pattern) {
  var str = target && target.toString ? target.toString() : target;

  return pattern instanceof RegExp  ? str.match(pattern) : str === pattern;
}
```
- example usage
```shell
...
    scope.__nock_filteredScope = scope.__nock_scopeKey;
    matchingInterceptor = interceptor.scopes;
    //  Break out of _.each for scopes.
    return false;
  }
});

if (!matchingInterceptor && common.matchStringOrRegexp(basePath, interceptor.key)) {
  matchingInterceptor = interceptor.scopes;
  // false to short circuit the .each
  return false;
}

//  Returning falsy value here (which will happen if we have found our matching interceptor)
//  will break out of _.each for all interceptors.
...
```

#### <a name="apidoc.element.nock.common.mergeChunks"></a>[function <span class="apidocSignatureSpan">nock.common.</span>mergeChunks (chunks)](#apidoc.element.nock.common.mergeChunks)
- description and source-code
```javascript
mergeChunks = function (chunks) {

  if(_.isEmpty(chunks)) {
    return new Buffer(0);
  }

  //  We assume that all chunks are Buffer objects if the first is buffer object.
  var areBuffers = Buffer.isBuffer(_.first(chunks));

  if(!areBuffers) {
    //  When the chunks are not buffers we assume that they are strings.
    return chunks.join('');
  }

  //  Merge all the buffers into a single Buffer object.
  return Buffer.concat(chunks);

}
```
- example usage
```shell
...
      }
    }

    return chunk.toString('hex');
  });
}

var mergedBuffer = common.mergeChunks(chunks);

//  The merged buffer can be one of three things:
//    1.  A binary buffer which then has to be recorded as a hex string.
//    2.  A string buffer which represents a JSON object.
//    3.  A string buffer which doesn't represent a JSON object.

if(common.isBinaryBuffer(mergedBuffer)) {
...
```

#### <a name="apidoc.element.nock.common.normalizeRequestOptions"></a>[function <span class="apidocSignatureSpan">nock.common.</span>normalizeRequestOptions (options)](#apidoc.element.nock.common.normalizeRequestOptions)
- description and source-code
```javascript
normalizeRequestOptions = function (options) {
  options.proto = options.proto || (options._https_ ? 'https': 'http');
  options.port = options.port || ((options.proto === 'http') ? 80 : 443);
  if (options.host) {
    debug('options.host:', options.host);
    if (! options.hostname) {
      if (options.host.split(':').length == 2) {
        options.hostname = options.host.split(':')[0];
      } else {
        options.hostname = options.host;
      }
    }
  }
  debug('options.hostname in the end: %j', options.hostname);
  options.host = (options.hostname || 'localhost') + ':' + options.port;
  debug('options.host in the end: %j', options.host);

  /// lowercase host names
  ['hostname', 'host'].forEach(function(attr) {
    if (options[attr]) {
      options[attr] = options[attr].toLowerCase();
    }
  });

  return options;
}
```
- example usage
```shell
...
    allowNetConnect = matcher;
  } else {
    allowNetConnect = /.*/;
  }
}

function isEnabledForNetConnect(options) {
  common.normalizeRequestOptions(options);

  var enabled = allowNetConnect && allowNetConnect.test(options.host);
  debug('Net connect', enabled ? '' : 'not', 'enabled for', options.host);
  return enabled;
}

/**
...
```

#### <a name="apidoc.element.nock.common.overrideRequests"></a>[function <span class="apidocSignatureSpan">nock.common.</span>overrideRequests (newRequest)](#apidoc.element.nock.common.overrideRequests)
- description and source-code
```javascript
overrideRequests = function (newRequest) {
  debug('overriding requests');

  ['http', 'https'].forEach(function(proto) {
    debug('- overriding request for', proto);

    var moduleName = proto, // 1 to 1 match of protocol and module is fortunate :)
        module = {
          http: require('http'),
          https: require('https')
        }[moduleName],
        overriddenRequest = module.request;

    if(requestOverride[moduleName]) {
      throw new Error('Module\'s request already overridden for ' + moduleName + ' protocol.');
    }

    //  Store the properties of the overridden request so that it can be restored later on.
    requestOverride[moduleName] = {
      module: module,
      request: overriddenRequest
    };

    module.request = function(options, callback) {
      // debug('request options:', options);
      return newRequest(proto, overriddenRequest.bind(module), options, callback);
    };

    debug('- overridden request for', proto);
  });
}
```
- example usage
```shell
...
throw new Error('Nock already active');
  }

  overrideClientRequest();

  // ----- Overriding http.request and https.request:

  common.overrideRequests(function(proto, overriddenRequest, options, callback) {
//  NOTE: overriddenRequest is already bound to its module.
var req,
    res;

if (typeof options === 'string') {
  options = parse(options);
}
...
```

#### <a name="apidoc.element.nock.common.percentDecode"></a>[function <span class="apidocSignatureSpan">nock.common.</span>percentDecode (str)](#apidoc.element.nock.common.percentDecode)
- description and source-code
```javascript
function percentDecode(str) {
  try {
    return decodeURIComponent(str.replace(/\+/g, ' '));
  } catch (e) {
    return str;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.nock.common.percentEncode"></a>[function <span class="apidocSignatureSpan">nock.common.</span>percentEncode (str)](#apidoc.element.nock.common.percentEncode)
- description and source-code
```javascript
function percentEncode(str) {
  return encodeURIComponent(str).replace(/[!'()*]/g, function(c) {
    return '%' + c.charCodeAt(0).toString(16).toUpperCase();
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.nock.common.restoreOverriddenRequests"></a>[function <span class="apidocSignatureSpan">nock.common.</span>restoreOverriddenRequests ()](#apidoc.element.nock.common.restoreOverriddenRequests)
- description and source-code
```javascript
restoreOverriddenRequests = function () {
  debug('restoring requests');

  //  Restore any overridden requests.
  _(requestOverride).keys().each(function(proto) {
    debug('- restoring request for', proto);

    var override = requestOverride[proto];
    if(override) {
      override.module.request = override.request;
      debug('- restored request for', proto);
    }
  });
  requestOverride = [];
}
```
- example usage
```shell
...
  }

  debug(thisRecordingId, 'restoring overridden requests before new overrides');
  //  To preserve backward compatibility (starting recording wasn't throwing if nock was already active)
  //  we restore any requests that may have been overridden by other parts of nock (e.g. intercept)
  //  NOTE: This is hacky as hell but it keeps the backward compatibility *and* allows correct
  //    behavior in the face of other modules also overriding ClientRequest.
  common.restoreOverriddenRequests();
  //  We restore ClientRequest as it messes with recording of modules that also override ClientRequest (e.g. xhr2)
  intercept.restoreOverriddenClientRequest();

  //  We override the requests so that we can save information on them before executing.
  common.overrideRequests(function(proto, overriddenRequest, options, callback) {

var bodyChunks = [];
...
```

#### <a name="apidoc.element.nock.common.stringifyRequest"></a>[function <span class="apidocSignatureSpan">nock.common.</span>stringifyRequest (options, body)](#apidoc.element.nock.common.stringifyRequest)
- description and source-code
```javascript
function stringifyRequest(options, body) {
  var method = options.method || 'GET';

  var port = options.port;
  if (! port) port = (options.proto == 'https' ? '443' : '80');

  if (options.proto == 'https' && port == '443' ||
      options.proto == 'http' && port == '80') {
    port = '';
  }

  if (port) port = ':' + port;

  var log = {
    method: method,
    url: options.proto + '://' + options.hostname + port + options.path,
    headers: options.headers
  };

  if (body) {
    log.body = body;
  }

  return JSON.stringify(log, null, 2);
}
```
- example usage
```shell
...
      propagate(newReq, req);
      //  We send the raw buffer as we received it, not as we interpreted it.
      newReq.end(requestBodyBuffer);
      return;
    }
  }

  var err = new Error("Nock: No match for request " + common.stringifyRequest(options, requestBody));
  err.statusCode = err.status = 404;
  emitError(err);
  return;
}

debug('interceptor identified, starting mocking');
...
```



# <a name="apidoc.module.nock.delayed_body"></a>[module nock.delayed_body](#apidoc.module.nock.delayed_body)

#### <a name="apidoc.element.nock.delayed_body.delayed_body"></a>[function <span class="apidocSignatureSpan">nock.</span>delayed_body (ms, body)](#apidoc.element.nock.delayed_body.delayed_body)
- description and source-code
```javascript
function DelayedBody(ms, body) {
  Transform.call(this);

  var self = this;
  var data = '';
  var ended = false;

  if (common.isStream(body)) {
    body.on('data', function (chunk) {
      data += Buffer.isBuffer(chunk) ? chunk.toString() : chunk;
    });

    body.once('end', function () {
      ended = true;
    });

    body.resume();
  }

  setTimeout(function () {
    if (common.isStream(body) && !ended) {
      body.once('end', function () {
        self.end(data);
      });
    } else {
      self.end(data || body);
    }
  }, ms);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.nock.delayed_body.super_"></a>[function <span class="apidocSignatureSpan">nock.delayed_body.</span>super_ (options)](#apidoc.element.nock.delayed_body.super_)
- description and source-code
```javascript
function Transform(options) {
  if (!(this instanceof Transform))
    return new Transform(options);

  Duplex.call(this, options);

  this._transformState = new TransformState(this);

  var stream = this;

  // start out asking for a readable event once data is transformed.
  this._readableState.needReadable = true;

  // we have implemented the _read method, and done the other things
  // that Readable wants before the first _read call, so unset the
  // sync guard flag.
  this._readableState.sync = false;

  if (options) {
    if (typeof options.transform === 'function')
      this._transform = options.transform;

    if (typeof options.flush === 'function')
      this._flush = options.flush;
  }

  // When the writable side finishes, then flush out anything remaining.
  this.once('prefinish', function() {
    if (typeof this._flush === 'function')
      this._flush(function(er) {
        done(stream, er);
      });
    else
      done(stream);
  });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.nock.delayed_body.prototype"></a>[module nock.delayed_body.prototype](#apidoc.module.nock.delayed_body.prototype)

#### <a name="apidoc.element.nock.delayed_body.prototype._transform"></a>[function <span class="apidocSignatureSpan">nock.delayed_body.prototype.</span>_transform (chunk, encoding, cb)](#apidoc.element.nock.delayed_body.prototype._transform)
- description and source-code
```javascript
_transform = function (chunk, encoding, cb) {
  this.push(chunk);
  process.nextTick(cb);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.nock.intercept"></a>[module nock.intercept](#apidoc.module.nock.intercept)

#### <a name="apidoc.element.nock.intercept.intercept"></a>[function <span class="apidocSignatureSpan">nock.</span>intercept (key, interceptor, scope, scopeOptions, host)](#apidoc.element.nock.intercept.intercept)
- description and source-code
```javascript
function add(key, interceptor, scope, scopeOptions, host) {
  if (! allInterceptors.hasOwnProperty(key)) {
    allInterceptors[key] = { key: key, scopes: [] };
  }
  interceptor.__nock_scope = scope;

  //  We need scope's key and scope options for scope filtering function (if defined)
  interceptor.__nock_scopeKey = key;
  interceptor.__nock_scopeOptions = scopeOptions;
  //  We need scope's host for setting correct request headers for filtered scopes.
  interceptor.__nock_scopeHost = host;
  interceptor.interceptionCounter = 0;

  allInterceptors[key].scopes.push(interceptor);
}
```
- example usage
```shell
...
  .reply(200, { hello: 'world' });
'''

## HTTP Verbs

Nock supports any HTTP verb, and it has convenience methods for the GET, POST, PUT, HEAD, DELETE, PATCH and MERGE HTTP verbs.

You can intercept any HTTP verb using '.intercept(path, verb [, requestBody [, options]])':

'''js
scope('http://my.domain.com')
  .intercept('/path', 'PATCH')
  .reply(304);
'''
...
```

#### <a name="apidoc.element.nock.intercept.activate"></a>[function <span class="apidocSignatureSpan">nock.intercept.</span>activate ()](#apidoc.element.nock.intercept.activate)
- description and source-code
```javascript
function activate() {

  if(originalClientRequest) {
    throw new Error('Nock already active');
  }

  overrideClientRequest();

  // ----- Overriding http.request and https.request:

  common.overrideRequests(function(proto, overriddenRequest, options, callback) {
    //  NOTE: overriddenRequest is already bound to its module.
    var req,
        res;

    if (typeof options === 'string') {
      options = parse(options);
    }
    options.proto = proto;

    var interceptors = interceptorsFor(options)

    if (isOn() && interceptors) {
      var matches = false,
          allowUnmocked = false;

      matches = !! _.find(interceptors, function(interceptor) {
        return interceptor.matchIndependentOfBody(options);
      });

      allowUnmocked = !! _.find(interceptors, function(interceptor) {
        return interceptor.options.allowUnmocked;
      });

      if (! matches && allowUnmocked) {
        if (proto === 'https') {
          var ClientRequest = http.ClientRequest;
          http.ClientRequest = originalClientRequest;
          req = overriddenRequest(options, callback);
          http.ClientRequest = ClientRequest;
        } else {
          req = overriddenRequest(options, callback);
        }
        globalEmitter.emit('no match', req);
        return req;
      }

      //  NOTE: Since we already overrode the http.ClientRequest we are in fact constructing
      //    our own OverriddenClientRequest.
      req = new http.ClientRequest(options);

      res = RequestOverrider(req, options, interceptors, remove);
      if (callback) {
        res.on('response', callback);
      }
      return req;
    } else {
      globalEmitter.emit('no match', options);
      if (isOff() || isEnabledForNetConnect(options)) {
        return overriddenRequest(options, callback);
      } else {
        var error = new NetConnectNotAllowedError(options.host, options.path);
        return new ErroringClientRequest(error);
      }
    }
  });

}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.nock.intercept.activeMocks"></a>[function <span class="apidocSignatureSpan">nock.intercept.</span>activeMocks ()](#apidoc.element.nock.intercept.activeMocks)
- description and source-code
```javascript
function activeMocks() {
  return _.flatten(_.map(interceptorScopes(), function(scope) {
    return scope.activeMocks();
  }));
}
```
- example usage
```shell
...
* [Optional Requests](#optional-requests)
* [Allow __unmocked__ requests on a mocked hostname](#allow-__unmocked__-requests-on-a-mocked-hostname)
- [Expectations](#expectations)
* [.isDone()](#isdone)
* [.cleanAll()](#cleanall)
* [.persist()](#persist)
* [.pendingMocks()](#pendingmocks)
* [.activeMocks()](#activemocks)
- [Logging](#logging)
- [Restoring](#restoring)
- [Turning Nock Off (experimental!)](#turning-nock-off-experimental)
- [Enable/Disable real HTTP request](#enabledisable-real-http-request)
- [Recording](#recording)
* ['dont_print' option](#dont_print-option)
* ['output_objects' option](#output_objects-option)
...
```

#### <a name="apidoc.element.nock.intercept.disableNetConnect"></a>[function <span class="apidocSignatureSpan">nock.intercept.</span>disableNetConnect ()](#apidoc.element.nock.intercept.disableNetConnect)
- description and source-code
```javascript
function disableNetConnect() {
  allowNetConnect = undefined;
}
```
- example usage
```shell
...
# Enable/Disable real HTTP request

As default, if you do not mock a host, a real HTTP request will do, but sometimes you should not permit real HTTP request, so...

For disabling real http requests.

'''js
nock.disableNetConnect();
'''

So, if you try to request any host not 'nocked', it will thrown an 'NetConnectNotAllowedError'.

'''js
nock.disableNetConnect();
var req = http.get('http://google.com/');
...
```

#### <a name="apidoc.element.nock.intercept.enableNetConnect"></a>[function <span class="apidocSignatureSpan">nock.intercept.</span>enableNetConnect (matcher)](#apidoc.element.nock.intercept.enableNetConnect)
- description and source-code
```javascript
function enableNetConnect(matcher) {
  if (_.isString(matcher)) {
    allowNetConnect = new RegExp(matcher);
  } else if (_.isObject(matcher) && _.isFunction(matcher.test)) {
    allowNetConnect = matcher;
  } else {
    allowNetConnect = /.*/;
  }
}
```
- example usage
```shell
...
// This code will log a NetConnectNotAllowedError with message:
// Nock: Not allow net connect for "google.com:80"
'''

For enabling real HTTP requests (the default behaviour).

'''js
nock.enableNetConnect();
'''

You could allow real HTTP request for certain host names by providing a string or a regular expression for the hostname:

'''js
// using a string
nock.enableNetConnect('amazon.com');
...
```

#### <a name="apidoc.element.nock.intercept.isActive"></a>[function <span class="apidocSignatureSpan">nock.intercept.</span>isActive ()](#apidoc.element.nock.intercept.isActive)
- description and source-code
```javascript
function isActive() {

  //  If ClientRequest has been overwritten by Nock then originalClientRequest is not undefined.
  //  This means that Nock has been activated.
  return !_.isUndefined(originalClientRequest);

}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.nock.intercept.isDone"></a>[function <span class="apidocSignatureSpan">nock.intercept.</span>isDone ()](#apidoc.element.nock.intercept.isDone)
- description and source-code
```javascript
function isDone() {
  return _.every(interceptorScopes(), function(scope) {
    return scope.isDone();
  });
}
```
- example usage
```shell
...
  * [Scope filtering](#scope-filtering)
  * [Path filtering](#path-filtering)
  * [Request Body filtering](#request-body-filtering)
  * [Request Headers Matching](#request-headers-matching)
  * [Optional Requests](#optional-requests)
  * [Allow __unmocked__ requests on a mocked hostname](#allow-__unmocked__-requests-on-a-mocked-hostname)
- [Expectations](#expectations)
  * [.isDone()](#isdone)
  * [.cleanAll()](#cleanall)
  * [.persist()](#persist)
  * [.pendingMocks()](#pendingmocks)
  * [.activeMocks()](#activemocks)
- [Logging](#logging)
- [Restoring](#restoring)
- [Turning Nock Off (experimental!)](#turning-nock-off-experimental)
...
```

#### <a name="apidoc.element.nock.intercept.isOn"></a>[function <span class="apidocSignatureSpan">nock.intercept.</span>isOn ()](#apidoc.element.nock.intercept.isOn)
- description and source-code
```javascript
function isOn() {
  return !isOff();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.nock.intercept.overrideClientRequest"></a>[function <span class="apidocSignatureSpan">nock.intercept.</span>overrideClientRequest ()](#apidoc.element.nock.intercept.overrideClientRequest)
- description and source-code
```javascript
function overrideClientRequest() {
  debug('Overriding ClientRequest');

  if(originalClientRequest) {
    throw new Error('Nock already overrode http.ClientRequest');
  }

  // ----- Extending http.ClientRequest

  //  Define the overriding client request that nock uses internally.
  function OverriddenClientRequest(options, cb) {
    if (http.OutgoingMessage) http.OutgoingMessage.call(this);

    //  Filter the interceptors per request options.
    var interceptors = interceptorsFor(options);

    if (isOn() && interceptors) {
      debug('using', interceptors.length, 'interceptors');

      //  Use filtered interceptors to intercept requests.
      var overrider = RequestOverrider(this, options, interceptors, remove, cb);
      for(var propName in overrider) {
        if (overrider.hasOwnProperty(propName)) {
          this[propName] = overrider[propName];
        }
      }
    } else {
      debug('falling back to original ClientRequest');

      //  Fallback to original ClientRequest if nock is off or the net connection is enabled.
      if(isOff() || isEnabledForNetConnect(options)) {
        originalClientRequest.apply(this, arguments);
      } else {
        timers.setImmediate(function () {
          var error = new NetConnectNotAllowedError(options.host, options.path);
          this.emit('error', error);
        }.bind(this));
      }
    }
  }
  if (http.ClientRequest) {
    inherits(OverriddenClientRequest, http.ClientRequest);
  } else {
    inherits(OverriddenClientRequest, EventEmitter);
  }

  //  Override the http module's request but keep the original so that we can use it and later restore it.
  //  NOTE: We only override http.ClientRequest as https module also uses it.
  originalClientRequest = http.ClientRequest;
  http.ClientRequest = OverriddenClientRequest;

  debug('ClientRequest overridden');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.nock.intercept.pendingMocks"></a>[function <span class="apidocSignatureSpan">nock.intercept.</span>pendingMocks ()](#apidoc.element.nock.intercept.pendingMocks)
- description and source-code
```javascript
function pendingMocks() {
  return _.flatten(_.map(interceptorScopes(), function(scope) {
    return scope.pendingMocks();
  }));
}
```
- example usage
```shell
...
* [Request Headers Matching](#request-headers-matching)
* [Optional Requests](#optional-requests)
* [Allow __unmocked__ requests on a mocked hostname](#allow-__unmocked__-requests-on-a-mocked-hostname)
- [Expectations](#expectations)
* [.isDone()](#isdone)
* [.cleanAll()](#cleanall)
* [.persist()](#persist)
* [.pendingMocks()](#pendingmocks)
* [.activeMocks()](#activemocks)
- [Logging](#logging)
- [Restoring](#restoring)
- [Turning Nock Off (experimental!)](#turning-nock-off-experimental)
- [Enable/Disable real HTTP request](#enabledisable-real-http-request)
- [Recording](#recording)
* ['dont_print' option](#dont_print-option)
...
```

#### <a name="apidoc.element.nock.intercept.removeAll"></a>[function <span class="apidocSignatureSpan">nock.intercept.</span>removeAll ()](#apidoc.element.nock.intercept.removeAll)
- description and source-code
```javascript
function removeAll() {
  allInterceptors = {};
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.nock.intercept.removeInterceptor"></a>[function <span class="apidocSignatureSpan">nock.intercept.</span>removeInterceptor (options)](#apidoc.element.nock.intercept.removeInterceptor)
- description and source-code
```javascript
function removeInterceptor(options) {
  var baseUrl, key, method, proto;
  if (options instanceof Interceptor) {
    baseUrl = options.basePath;
    key = options._key;
  } else {
    proto = options.proto ? options.proto : 'http';

    common.normalizeRequestOptions(options);
    baseUrl = proto + '://' + options.host;
    method = options.method && options.method.toUpperCase() || 'GET';
    key = method + ' ' + baseUrl + (options.path || '/');
  }

  if (allInterceptors[baseUrl] && allInterceptors[baseUrl].scopes.length > 0) {
    if (key) {
      for (var i = 0; i < allInterceptors[baseUrl].scopes.length; i++) {
        var interceptor = allInterceptors[baseUrl].scopes[i];
        if (interceptor._key === key) {
          allInterceptors[baseUrl].scopes.splice(i, 1);
          interceptor.scope.remove(key, interceptor);
          break;
        }
      }
    } else {
      allInterceptors[baseUrl].scopes.length = 0;
    }

    return true;
  }

  return false;
}
```
- example usage
```shell
...
- [Enable/Disable real HTTP request](#enabledisable-real-http-request)
- [Recording](#recording)
* ['dont_print' option](#dont_print-option)
* ['output_objects' option](#output_objects-option)
* ['enable_reqheaders_recording' option](#enable_reqheaders_recording-option)
* ['logging' option](#logging-option)
* ['use_separator' option](#use_separator-option)
* [.removeInterceptor()](#removeinterceptor)
- [Events](#events)
* [Global no match event](#global-no-match-event)
- [Nock Back](#nock-back)
* [Setup](#setup)
  + [Options](#options)
* [Usage](#usage)
  + [Options](#options-1)
...
```

#### <a name="apidoc.element.nock.intercept.restoreOverriddenClientRequest"></a>[function <span class="apidocSignatureSpan">nock.intercept.</span>restoreOverriddenClientRequest ()](#apidoc.element.nock.intercept.restoreOverriddenClientRequest)
- description and source-code
```javascript
function restoreOverriddenClientRequest() {
  debug('restoring overriden ClientRequest');

  //  Restore the ClientRequest we have overridden.
  if(!originalClientRequest) {
    debug('- ClientRequest was not overridden');
  } else {
    http.ClientRequest = originalClientRequest;
    originalClientRequest = undefined;

    debug('- ClientRequest restored');
  }
}
```
- example usage
```shell
...
  debug(thisRecordingId, 'restoring overridden requests before new overrides');
  //  To preserve backward compatibility (starting recording wasn't throwing if nock was already active)
  //  we restore any requests that may have been overridden by other parts of nock (e.g. intercept)
  //  NOTE: This is hacky as hell but it keeps the backward compatibility *and* allows correct
  //    behavior in the face of other modules also overriding ClientRequest.
  common.restoreOverriddenRequests();
  //  We restore ClientRequest as it messes with recording of modules that also override ClientRequest (e.g. xhr2)
  intercept.restoreOverriddenClientRequest();

  //  We override the requests so that we can save information on them before executing.
  common.overrideRequests(function(proto, overriddenRequest, options, callback) {

var bodyChunks = [];

if (typeof options == 'string') {
...
```



# <a name="apidoc.module.nock.interceptor"></a>[module nock.interceptor](#apidoc.module.nock.interceptor)

#### <a name="apidoc.element.nock.interceptor.interceptor"></a>[function <span class="apidocSignatureSpan">nock.</span>interceptor (scope, uri, method, requestBody, interceptorOptions)](#apidoc.element.nock.interceptor.interceptor)
- description and source-code
```javascript
function Interceptor(scope, uri, method, requestBody, interceptorOptions) {
    this.scope = scope;
    this.interceptorMatchHeaders = [];
    this.method = method.toUpperCase();
    this.uri = uri;
    this._key = this.method + ' ' + scope.basePath + scope.basePathname + (typeof uri === 'string' ? '' : '/') + uri;
    this.basePath = this.scope.basePath;
    this.path = (typeof uri === 'string') ? scope.basePathname + uri : uri;

    this.baseUri = this.method + ' ' + scope.basePath + scope.basePathname;
    this.options = interceptorOptions || {};
    this.counter = 1;
    this._requestBody = requestBody;

    //  We use lower-case header field names throughout Nock.
    this.reqheaders = common.headersFieldNamesToLowerCase((scope.scopeOptions && scope.scopeOptions.reqheaders) || {});
    this.badheaders = common.headersFieldsArrayToLowerCase((scope.scopeOptions && scope.scopeOptions.badheaders) || []);


    this.delayInMs = 0;
    this.delayConnectionInMs = 0;

    this.optional = false;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.nock.interceptor.prototype"></a>[module nock.interceptor.prototype](#apidoc.module.nock.interceptor.prototype)

#### <a name="apidoc.element.nock.interceptor.prototype.basicAuth"></a>[function <span class="apidocSignatureSpan">nock.interceptor.prototype.</span>basicAuth (options)](#apidoc.element.nock.interceptor.prototype.basicAuth)
- description and source-code
```javascript
function basicAuth(options) {
    var username = options['user'];
    var password = options['pass'] || '';
    var name = 'authorization';
    var value = 'Basic ' + new Buffer(username + ':' + password).toString('base64');
    this.interceptorMatchHeaders.push({ name: name, value: value });
    return this;
}
```
- example usage
```shell
...
When invoked with this option, Nock will not match the request if any of the 'badheaders' are present.

Basic authentication can be specified as follows:

'''js
var scope = nock('http://www.example.com')
    .get('/')
    .basicAuth({
      user: 'john',
      pass: 'doe'
    })
    .reply(200);
'''

### Specifying Reply Headers
...
```

#### <a name="apidoc.element.nock.interceptor.prototype.delay"></a>[function <span class="apidocSignatureSpan">nock.interceptor.prototype.</span>delay (opts)](#apidoc.element.nock.interceptor.prototype.delay)
- description and source-code
```javascript
function delay(opts) {
    var headDelay = 0;
    var bodyDelay = 0;
    if (_.isNumber(opts)) {
        headDelay = opts;
    } else if (_.isObject(opts)) {
        headDelay = opts.head || 0;
        bodyDelay = opts.body || 0;
    } else {
        throw new Error("Unexpected input opts" + opts);
    }

    return this.delayConnection(headDelay)
        .delayBody(bodyDelay);
}
```
- example usage
```shell
...
## Delay the response

You are able to specify the number of milliseconds that your reply should be delayed.

'''js
nock('http://my.server.com')
 .get('/')
 .delay(2000) // 2 seconds delay will be applied to the response header.
 .reply(200, '<html></html>')
'''

'delay()' could also be used as

'''
delay({
...
```

#### <a name="apidoc.element.nock.interceptor.prototype.delayBody"></a>[function <span class="apidocSignatureSpan">nock.interceptor.prototype.</span>delayBody (ms)](#apidoc.element.nock.interceptor.prototype.delayBody)
- description and source-code
```javascript
function delayBody(ms) {
    this.delayInMs += ms;
    return this;
}
```
- example usage
```shell
...
You are able to specify the number of milliseconds that the response body should be delayed. Response header will be replied immediately
.
'delayBody(1000)' is equivalent to 'delay({body: 1000})'.


'''js
nock('http://my.server.com')
  .get('/')
  .delayBody(2000) // 2 seconds
  .reply(200, '<html></html>')
'''

NOTE: the [''response''](http://nodejs.org/api/http.html#http_event_response) event will occur immediately, but the [IncomingMessage
](http://nodejs.org/api/http.html#http_http_incomingmessage) not emit it's ''end'' event until after the delay.

## Delay the response
...
```

#### <a name="apidoc.element.nock.interceptor.prototype.delayConnection"></a>[function <span class="apidocSignatureSpan">nock.interceptor.prototype.</span>delayConnection (ms)](#apidoc.element.nock.interceptor.prototype.delayConnection)
- description and source-code
```javascript
function delayConnection(ms) {
    this.delayConnectionInMs += ms;
    return this;
}
```
- example usage
```shell
...
   } else if (_.isObject(opts)) {
       headDelay = opts.head || 0;
       bodyDelay = opts.body || 0;
   } else {
       throw new Error("Unexpected input opts" + opts);
   }

   return this.delayConnection(headDelay)
       .delayBody(bodyDelay);
};

/**
* Delay the response body by a certain number of ms.
*
* @param {integer} ms - Number of milliseconds to wait before response is sent
...
```

#### <a name="apidoc.element.nock.interceptor.prototype.discard"></a>[function <span class="apidocSignatureSpan">nock.interceptor.prototype.</span>discard ()](#apidoc.element.nock.interceptor.prototype.discard)
- description and source-code
```javascript
function discard() {
    if ((this.scope.shouldPersist() || this.counter > 0) && this.filePath) {
        this.body = fs.createReadStream(this.filePath);
        this.body.pause();
    }

    if (!this.scope.shouldPersist() && this.counter < 1) {
        this.scope.remove(this._key, this);
    }
}
```
- example usage
```shell
...
    req.headers = req._headers;

    interceptor.scope.emit('request', req, interceptor);

    if (typeof interceptor.errorMessage !== 'undefined') {
interceptor.interceptionCounter++;
remove(interceptor);
interceptor.discard();

var error;
if (_.isObject(interceptor.errorMessage)) {
  error = interceptor.errorMessage;
} else {
  error = new Error(interceptor.errorMessage);
}
...
```

#### <a name="apidoc.element.nock.interceptor.prototype.filteringPath"></a>[function <span class="apidocSignatureSpan">nock.interceptor.prototype.</span>filteringPath ()](#apidoc.element.nock.interceptor.prototype.filteringPath)
- description and source-code
```javascript
function filteringPath() {
    if (_.isFunction(arguments[0])) {
        this.scope.transformFunction = arguments[0];
    }
    return this;
}
```
- example usage
```shell
...

This can be useful, for instance, if you have random or time-dependent data in your URL.

You can use a regexp for replacement, just like String.prototype.replace:

'''js
var scope = nock('http://api.myservice.com')
                .filteringPath(/password=[^&]*/g, 'password=XXX')
                .get('/users/1?password=XXX')
                .reply(200, 'user');
'''

Or you can use a function:

'''js
...
```

#### <a name="apidoc.element.nock.interceptor.prototype.getTotalDelay"></a>[function <span class="apidocSignatureSpan">nock.interceptor.prototype.</span>getTotalDelay ()](#apidoc.element.nock.interceptor.prototype.getTotalDelay)
- description and source-code
```javascript
function getTotalDelay() {
    return this.delayInMs + this.delayConnectionInMs;
}
```
- example usage
```shell
...

  var error;
  if (_.isObject(interceptor.errorMessage)) {
    error = interceptor.errorMessage;
  } else {
    error = new Error(interceptor.errorMessage);
  }
  timers.setTimeout(emitError, interceptor.getTotalDelay(), error);
  return;
}
response.statusCode = Number(interceptor.statusCode) || 200;

// Clone headers/rawHeaders to not override them when evaluating later
response.headers = _.extend({}, interceptor.headers);
response.rawHeaders = (interceptor.rawHeaders || []).slice();
...
```

#### <a name="apidoc.element.nock.interceptor.prototype.match"></a>[function <span class="apidocSignatureSpan">nock.interceptor.prototype.</span>match (options, body, hostNameOnly)](#apidoc.element.nock.interceptor.prototype.match)
- description and source-code
```javascript
function match(options, body, hostNameOnly) {
    if (debug.enabled) {
        debug('match %s, body = %s', stringify(options), stringify(body));
    }

    if (hostNameOnly) {
        return options.hostname === this.scope.urlParts.hostname;
    }

    var method = (options.method || 'GET').toUpperCase()
        , path = options.path
        , matches
        , matchKey
        , proto = options.proto;

    if (this.scope.transformPathFunction) {
        path = this.scope.transformPathFunction(path);
    }
    if (typeof(body) !== 'string') {
        body = body.toString();
    }
    if (this.scope.transformRequestBodyFunction) {
        body = this.scope.transformRequestBodyFunction(body, this._requestBody);
    }

    var checkHeaders = function(header) {
        if (_.isFunction(header.value)) {
            return header.value(options.getHeader(header.name));
        }
        return common.matchStringOrRegexp(options.getHeader(header.name), header.value);
    };

    if (!this.scope.matchHeaders.every(checkHeaders) ||
        !this.interceptorMatchHeaders.every(checkHeaders)) {
        this.scope.logger('headers don\'t match');
        return false;
    }

    var reqHeadersMatch =
        ! this.reqheaders ||
        Object.keys(this.reqheaders).every(this.reqheaderMatches.bind(this, options));

    if (!reqHeadersMatch) {
        return false;
    }

    function reqheaderContains(header) {
        return _.has(options.headers, header);
    }

    var reqContainsBadHeaders =
        this.badheaders &&
        _.some(this.badheaders, reqheaderContains);

    if (reqContainsBadHeaders) {
        return false;
    }

    //  If we have a filtered scope then we use it instead reconstructing
    //  the scope from the request options (proto, host and port) as these
    //  two won't necessarily match and we have to remove the scope that was
    //  matched (vs. that was defined).
    if (this.__nock_filteredScope) {
        matchKey = this.__nock_filteredScope;
    } else {
        matchKey = proto + '://' + options.host;
        if (
            options.port && options.host.indexOf(':') < 0 &&
            (options.port !== 80 || options.proto !== 'http') &&
            (options.port !== 443 || options.proto !== 'https')
        ) {
            matchKey += ":" + options.port;
        }
    }

    // Match query strings when using query()
    var matchQueries = true;
    var queryIndex = -1;
    var queryString;
    var queries;

    if (this.queries) {
        queryIndex = path.indexOf('?');
        queryString = (queryIndex !== -1) ? path.slice(queryIndex + 1) : '';
        queries = qs.parse(queryString);

        // Only check for query string matches if this.queries is an object
        if (_.isObject(this.queries)) {

            if(_.isFunction(this.queries)){
                matchQueries = this.queries(queries);
            }else {
                // Make sure that you have an equal number of keys. We are
                // looping through the passed query params and not the expected values
                // if the user passes fewer query params than expected but all values
                // match this will throw a false positive. Testing that the length of the
                // passed query params is equal to the length of expected keys will prevent
                // us from doing any value checking BEFORE we know if they have all the proper
                // params
                debug('this.queries: %j', this.queries);
                debug('queries: %j', queries);
                if (_.size(this.queries) !== _.size(queries)) {
                    matchQueries = false;
                } else {
                    var self = this;
                    _.forOwn(queries, function matchOneKeyVal(val, key) {
                        var expVal = self.queries[key];
                        var isMatch = true;
                        if (val === undefined || expVal === undefined) {
                        isMatch = false;
                    } else if (expVal instanceof RegExp) {
                      isMatch = c ...
```
- example usage
```shell
...
  return '%' + c.charCodeAt(0).toString(16).toUpperCase();
});
}

function matchStringOrRegexp(target, pattern) {
var str = target && target.toString ? target.toString() : target;

return pattern instanceof RegExp  ? str.match(pattern) : str === pattern;
}

// return [newKey, newValue]
function formatQueryValue(key, value, options) {
switch (true) {
  case _.isNumber(value): // fall-though
  case _.isBoolean(value):
...
```

#### <a name="apidoc.element.nock.interceptor.prototype.matchHeader"></a>[function <span class="apidocSignatureSpan">nock.interceptor.prototype.</span>matchHeader (name, value)](#apidoc.element.nock.interceptor.prototype.matchHeader)
- description and source-code
```javascript
function matchHeader(name, value) {
    this.interceptorMatchHeaders.push({ name: name, value: value });
    return this;
}
```
- example usage
```shell
...

## Request Headers Matching

If you need to match requests only if certain request headers match, you can.

'''js
var scope = nock('http://api.myservice.com')
                .matchHeader('accept', 'application/json')
                .get('/')
                .reply(200, {
                  data: 'hello world'
                })
'''

You can also use a regexp for the header body.
...
```

#### <a name="apidoc.element.nock.interceptor.prototype.matchIndependentOfBody"></a>[function <span class="apidocSignatureSpan">nock.interceptor.prototype.</span>matchIndependentOfBody (options)](#apidoc.element.nock.interceptor.prototype.matchIndependentOfBody)
- description and source-code
```javascript
function matchIndependentOfBody(options) {
    var method = (options.method || 'GET').toUpperCase()
        , path = options.path
        , proto = options.proto;

    if (this.scope.transformPathFunction) {
        path = this.scope.transformPathFunction(path);
    }

    var checkHeaders = function(header) {
        return options.getHeader && common.matchStringOrRegexp(options.getHeader(header.name), header.value);
    };

    if (!this.scope.matchHeaders.every(checkHeaders) ||
        !this.interceptorMatchHeaders.every(checkHeaders)) {
        return false;
    }

    var matchKey = method + ' ' + proto + '://' + options.host + path;
    return this._key === matchKey;
}
```
- example usage
```shell
...
    var interceptors = interceptorsFor(options)

    if (isOn() && interceptors) {
var matches = false,
    allowUnmocked = false;

matches = !! _.find(interceptors, function(interceptor) {
  return interceptor.matchIndependentOfBody(options);
});

allowUnmocked = !! _.find(interceptors, function(interceptor) {
  return interceptor.options.allowUnmocked;
});

if (! matches && allowUnmocked) {
...
```

#### <a name="apidoc.element.nock.interceptor.prototype.once"></a>[function <span class="apidocSignatureSpan">nock.interceptor.prototype.</span>once ()](#apidoc.element.nock.interceptor.prototype.once)
- description and source-code
```javascript
function once() {
    return this.times(1);
}
```
- example usage
```shell
...
http.get('http://zombo.com/'); // respond body "Ok"
http.get('http://zombo.com/'); // respond with zombo.com result
'''

Sugar syntax

'''js
nock('http://zombo.com').get('/').once().reply(200, 'Ok');
nock('http://zombo.com').get('/').twice().reply(200, 'Ok');
nock('http://zombo.com').get('/').thrice().reply(200, 'Ok');
'''

## Delay the response body
You are able to specify the number of milliseconds that the response body should be delayed. Response header will be replied immediately
.
'delayBody(1000)' is equivalent to 'delay({body: 1000})'.
...
```

#### <a name="apidoc.element.nock.interceptor.prototype.optionally"></a>[function <span class="apidocSignatureSpan">nock.interceptor.prototype.</span>optionally ()](#apidoc.element.nock.interceptor.prototype.optionally)
- description and source-code
```javascript
function optionally() {
    this.optional = true;
    return this;
}
```
- example usage
```shell
...
example.pendingMocks() // []
example.get("/pathA").reply(200);
example.pendingMocks() // ["GET http://example.com:80/path"]

// ...After a request to example.com/pathA:
example.pendingMocks() // []

example.get("/pathB").optionally().reply(200);
example.pendingMocks() // []
'''

## Allow __unmocked__ requests on a mocked hostname

If you need some request on the same host name to be mocked and some others to **really** go through the HTTP stack, you can use
 the 'allowUnmocked' option like this:
...
```

#### <a name="apidoc.element.nock.interceptor.prototype.query"></a>[function <span class="apidocSignatureSpan">nock.interceptor.prototype.</span>query (queries)](#apidoc.element.nock.interceptor.prototype.query)
- description and source-code
```javascript
function query(queries) {
    this.queries = this.queries || {};
    // Allow all query strings to match this route
    if (queries === true) {
        this.queries = queries;
    }

    if(_.isFunction(queries)){
        this.queries = queries;
        return this;
    }

    for (var q in queries) {
        if (_.isUndefined(this.queries[q])) {
            var value = queries[q];
            var formatedPair = common.formatQueryValue(q, value, this.scope.scopeOptions);
            this.queries[formatedPair[0]] = formatedPair[1];
        }
    }

    return this;
}
```
- example usage
```shell
...
## Specifying request query string

Nock understands query strings. Instead of placing the entire URL, you can specify the query part as an object:

'''js
nock('http://example.com')
  .get('/users')
  .query({name: 'pedro', surname: 'teixeira'})
  .reply(200, {results: [{id: 'pgte'}]});
'''

Nock supports array-style/object-style query parameters. The encoding format matches with request module.

'''js
nock('http://example.com')
...
```

#### <a name="apidoc.element.nock.interceptor.prototype.reply"></a>[function <span class="apidocSignatureSpan">nock.interceptor.prototype.</span>reply (statusCode, body, rawHeaders)](#apidoc.element.nock.interceptor.prototype.reply)
- description and source-code
```javascript
function reply(statusCode, body, rawHeaders) {
    if (arguments.length <= 2 && _.isFunction(statusCode)) {
        body = statusCode;
        statusCode = 200;
    }

    this.statusCode = statusCode;

    _.defaults(this.options, this.scope.scopeOptions);

    // convert rawHeaders from Array to Object
    var headers = common.headersArrayToObject(rawHeaders);

    if (this.scope._defaultReplyHeaders) {
        headers = headers || {};
        headers = mixin(this.scope._defaultReplyHeaders, headers);
    }

    if (this.scope.date) {
        headers = headers || {};
        headers['date'] = this.scope.date.toUTCString();
    }

    if (headers !== undefined) {
        this.rawHeaders = [];

        // makes sure all keys in headers are in lower case
        for (var key in headers) {
            if (headers.hasOwnProperty(key)) {
                this.rawHeaders.push(key);
                this.rawHeaders.push(headers[key]);
            }
        }

        //  We use lower-case headers throughout Nock.
        this.headers = common.headersFieldNamesToLowerCase(headers);

        debug('reply.headers:', this.headers);
        debug('reply.rawHeaders:', this.rawHeaders);
    }

    //  If the content is not encoded we may need to transform the response body.
    //  Otherwise we leave it as it is.
    if (!common.isContentEncoded(this.headers)) {
        if (body && typeof(body) !== 'string' &&
            typeof(body) !== 'function' &&
            !Buffer.isBuffer(body) &&
            !common.isStream(body)) {
            try {
                body = stringify(body);
                if (!this.headers) {
                    this.headers = {};
                }
                if (!this.headers['content-type']) {
                    this.headers['content-type'] = 'application/json';
                }
                if (this.scope.contentLen) {
                    this.headers['content-length'] = body.length;
                }
            } catch(err) {
                throw new Error('Error encoding response body into JSON');
            }
        }
    }

    this.body = body;

    this.scope.add(this._key, this, this.scope, this.scopeOptions);
    return this.scope;
}
```
- example usage
```shell
...
On your test, you can setup your mocking object like this:

'''js
var nock = require('nock');

var couchdb = nock('http://myapp.iriscouch.com')
                .get('/users/1')
                .reply(200, {
                  _id: '123ABC',
                  _rev: '946B7D1C',
                  username: 'pgte',
                  email: 'pedro.teixeira@gmail.com'
                 });
'''
...
```

#### <a name="apidoc.element.nock.interceptor.prototype.replyWithError"></a>[function <span class="apidocSignatureSpan">nock.interceptor.prototype.</span>replyWithError (errorMessage)](#apidoc.element.nock.interceptor.prototype.replyWithError)
- description and source-code
```javascript
function replyWithError(errorMessage) {
    this.errorMessage = errorMessage;

    _.defaults(this.options, this.scope.scopeOptions);

    this.scope.add(this._key, this, this.scope, this.scopeOptions);
    return this.scope;
}
```
- example usage
```shell
...
### Replying with errors

You can reply with an error like this:

'''js
nock('http://www.google.com')
 .get('/cat-poems')
 .replyWithError('something awful happened');
'''

JSON error responses are allowed too:

'''js
nock('http://www.google.com')
.get('/cat-poems')
...
```

#### <a name="apidoc.element.nock.interceptor.prototype.replyWithFile"></a>[function <span class="apidocSignatureSpan">nock.interceptor.prototype.</span>replyWithFile (statusCode, filePath, headers)](#apidoc.element.nock.interceptor.prototype.replyWithFile)
- description and source-code
```javascript
function replyWithFile(statusCode, filePath, headers) {
    if (! fs) {
        throw new Error('No fs');
    }
    var readStream = fs.createReadStream(filePath);
    readStream.pause();
    this.filePath = filePath;
    return this.reply(statusCode, readStream, headers);
}
```
- example usage
```shell
...
'''

or even as a file:

'''js
var scope = nock('http://myapp.iriscouch.com')
             .get('/')
             .replyWithFile(200, __dirname + '/replies/user.json');
'''

Instead of an object or a buffer you can also pass in a callback to be evaluated for the value of the response body:

'''js
var scope = nock('http://www.google.com')
.filteringRequestBody(/.*/, '*')
...
```

#### <a name="apidoc.element.nock.interceptor.prototype.reqheaderMatches"></a>[function <span class="apidocSignatureSpan">nock.interceptor.prototype.</span>reqheaderMatches (options, key)](#apidoc.element.nock.interceptor.prototype.reqheaderMatches)
- description and source-code
```javascript
function reqheaderMatches(options, key) {
    //  We don't try to match request headers if these weren't even specified in the request.
    if (! options.headers) {
        return true;
    }

    var reqHeader = this.reqheaders[key];
    var header = options.headers[key];
    if (header && (typeof header !== 'string') && header.toString) {
        header = header.toString();
    }

    //  We skip 'host' header comparison unless it's available in both mock and actual request.
    //  This because 'host' may get inserted by Nock itself and then get recorder.
    //  NOTE: We use lower-case header field names throughout Nock.
    if (key === 'host' &&
        (_.isUndefined(header) ||
        _.isUndefined(reqHeader)))
    {
        return true;
    }

    if (reqHeader && header) {
        if (_.isFunction(reqHeader)) {
            return reqHeader(header);
        } else if (common.matchStringOrRegexp(header, reqHeader)) {
            return true;
        }
    }

    debug('request header field doesn\'t match:', key, header, reqHeader);
    return false;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.nock.interceptor.prototype.socketDelay"></a>[function <span class="apidocSignatureSpan">nock.interceptor.prototype.</span>socketDelay (ms)](#apidoc.element.nock.interceptor.prototype.socketDelay)
- description and source-code
```javascript
function socketDelay(ms) {
    this.socketDelayInMs = ms;
    return this;
}
```
- example usage
```shell
...
## Socket timeout

You are able to specify the number of milliseconds that your connection should be idle, to simulate a socket timeout.

'''js
nock('http://my.server.com')
  .get('/')
  .socketDelay(2000) // 2 seconds
  .reply(200, '<html></html>')
'''

To test a request like the following:

'''js
req = http.request('http://my.server.com', function(res) {
...
```

#### <a name="apidoc.element.nock.interceptor.prototype.thrice"></a>[function <span class="apidocSignatureSpan">nock.interceptor.prototype.</span>thrice ()](#apidoc.element.nock.interceptor.prototype.thrice)
- description and source-code
```javascript
function thrice() {
    return this.times(3);
}
```
- example usage
```shell
...
'''

Sugar syntax

'''js
nock('http://zombo.com').get('/').once().reply(200, 'Ok');
nock('http://zombo.com').get('/').twice().reply(200, 'Ok');
nock('http://zombo.com').get('/').thrice().reply(200, 'Ok');
'''

## Delay the response body
You are able to specify the number of milliseconds that the response body should be delayed. Response header will be replied immediately
.
'delayBody(1000)' is equivalent to 'delay({body: 1000})'.
...
```

#### <a name="apidoc.element.nock.interceptor.prototype.times"></a>[function <span class="apidocSignatureSpan">nock.interceptor.prototype.</span>times (newCounter)](#apidoc.element.nock.interceptor.prototype.times)
- description and source-code
```javascript
function times(newCounter) {
    if (newCounter < 1) {
        return this;
    }

    this.counter = newCounter;

    return this;
}
```
- example usage
```shell
...
'''

## Repeat response n times

You are able to specify the number of times to repeat the same response.

'''js
nock('http://zombo.com').get('/').times(4).reply(200, 'Ok');

http.get('http://zombo.com/'); // respond body "Ok"
http.get('http://zombo.com/'); // respond body "Ok"
http.get('http://zombo.com/'); // respond body "Ok"
http.get('http://zombo.com/'); // respond body "Ok"
http.get('http://zombo.com/'); // respond with zombo.com result
'''
...
```

#### <a name="apidoc.element.nock.interceptor.prototype.twice"></a>[function <span class="apidocSignatureSpan">nock.interceptor.prototype.</span>twice ()](#apidoc.element.nock.interceptor.prototype.twice)
- description and source-code
```javascript
function twice() {
    return this.times(2);
}
```
- example usage
```shell
...
http.get('http://zombo.com/'); // respond with zombo.com result
'''

Sugar syntax

'''js
nock('http://zombo.com').get('/').once().reply(200, 'Ok');
nock('http://zombo.com').get('/').twice().reply(200, 'Ok');
nock('http://zombo.com').get('/').thrice().reply(200, 'Ok');
'''

## Delay the response body
You are able to specify the number of milliseconds that the response body should be delayed. Response header will be replied immediately
.
'delayBody(1000)' is equivalent to 'delay({body: 1000})'.
...
```



# <a name="apidoc.module.nock.recorder"></a>[module nock.recorder](#apidoc.module.nock.recorder)

#### <a name="apidoc.element.nock.recorder.clear"></a>[function <span class="apidocSignatureSpan">nock.recorder.</span>clear ()](#apidoc.element.nock.recorder.clear)
- description and source-code
```javascript
function clear() {
  outputs = [];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.nock.recorder.play"></a>[function <span class="apidocSignatureSpan">nock.recorder.</span>play ()](#apidoc.element.nock.recorder.play)
- description and source-code
```javascript
play = function () {
  return outputs;
}
```
- example usage
```shell
...
If you just want to capture the generated code into a var as an array you can use:

'''js
nock.recorder.rec({
  dont_print: true
});
// ... some HTTP calls
var nockCalls = nock.recorder.play();
'''

The 'nockCalls' var will contain an array of strings representing the generated code you need.

Copy and paste that code into your tests, customize at will, and you're done!

(Remember that you should do this one test at a time).
...
```

#### <a name="apidoc.element.nock.recorder.rec"></a>[function <span class="apidocSignatureSpan">nock.recorder.</span>rec (rec_options)](#apidoc.element.nock.recorder.rec)
- description and source-code
```javascript
function record(rec_options) {

  //  Set the new current recording ID and capture its value in this instance of record().
  currentRecordingId = currentRecordingId + 1;
  var thisRecordingId = currentRecordingId;

  debug('start recording', thisRecordingId, JSON.stringify(rec_options));

  //  Trying to start recording with recording already in progress implies an error
  //  in the recording configuration (double recording makes no sense and used to lead
  //  to duplicates in output)
  if(recordingInProgress) {
    throw new Error('Nock recording already in progress');
  }

  recordingInProgress = true;

  //  Originaly the parameters was a dont_print boolean flag.
  //  To keep the existing code compatible we take that case into account.
  var optionsIsObject = typeof rec_options === 'object';
  var dont_print = (typeof rec_options === 'boolean' && rec_options) ||
      (optionsIsObject && rec_options.dont_print);
  var output_objects = optionsIsObject && rec_options.output_objects;
  var enable_reqheaders_recording = optionsIsObject && rec_options.enable_reqheaders_recording;
  var logging = (optionsIsObject && rec_options.logging) || console.log;
  var use_separator = true;
  if (optionsIsObject && _.has(rec_options, 'use_separator')) {
    use_separator = rec_options.use_separator;
  }

  debug(thisRecordingId, 'restoring overridden requests before new overrides');
  //  To preserve backward compatibility (starting recording wasn't throwing if nock was already active)
  //  we restore any requests that may have been overridden by other parts of nock (e.g. intercept)
  //  NOTE: This is hacky as hell but it keeps the backward compatibility *and* allows correct
  //    behavior in the face of other modules also overriding ClientRequest.
  common.restoreOverriddenRequests();
  //  We restore ClientRequest as it messes with recording of modules that also override ClientRequest (e.g. xhr2)
  intercept.restoreOverriddenClientRequest();

  //  We override the requests so that we can save information on them before executing.
  common.overrideRequests(function(proto, overriddenRequest, options, callback) {

    var bodyChunks = [];

    if (typeof options == 'string') {
      var url = URL.parse(options);
      options = {
        hostname: url.hostname,
        method: 'GET',
        port: url.port,
        path: url.path
      };
    }

    // Node 0.11 https.request calls http.request -- don't want to record things
    // twice.
    if (options._recording) {
      return overriddenRequest(options, callback);
    }
    options._recording = true;

    var req = overriddenRequest(options, function(res) {

      debug(thisRecordingId, 'intercepting', proto, 'request to record');

      if (typeof options === 'string') {
        options = parse(options);
      }

      //  We put our 'end' listener to the front of the listener array.
      res.once('end', function() {
        debug(thisRecordingId, proto, 'intercepted request ended');

        var out;
        if(output_objects) {
          out = generateRequestAndResponseObject(req, bodyChunks, options, res, dataChunks);
          if(out.reqheaders) {
            //  We never record user-agent headers as they are worse than useless -
            //  they actually make testing more difficult without providing any benefit (see README)
            common.deleteHeadersField(out.reqheaders, 'user-agent');

            //  Remove request headers completely unless it was explicitly enabled by the user (see README)
            if(!enable_reqheaders_recording) {
              delete out.reqheaders;
            }
          }
        } else {
          out = generateRequestAndResponse(req, bodyChunks, options, res, dataChunks);
        }

        debug('out:', out);

        //  Check that the request was made during the current recording.
        //  If it hasn't then skip it. There is no other simple way to handle
        //  this as it depends on the timing of requests and responses. Throwing
        //  will make some recordings/unit tests faily randomly depending on how ...
```
- example usage
```shell
...
This is a cool feature:

Guessing what the HTTP calls are is a mess, specially if you are introducing nock on your already-coded tests.

For these cases where you want to mock an existing live system you can record and playback the HTTP calls like this:

'''js
nock.recorder.rec();
// Some HTTP calls happen and the nock code necessary to mock
// those calls will be outputted to console
'''

Recording relies on intercepting real requests and answers and then persisting them for later use.

**ATTENTION!:** when recording is enabled, nock does no validation.
...
```



# <a name="apidoc.module.nock.socket"></a>[module nock.socket](#apidoc.module.nock.socket)

#### <a name="apidoc.element.nock.socket.socket"></a>[function <span class="apidocSignatureSpan">nock.</span>socket (options)](#apidoc.element.nock.socket.socket)
- description and source-code
```javascript
function Socket(options) {
  if (!(this instanceof Socket)) {
    return new Socket(options);
  }

  EventEmitter.apply(this);

  options = options || {};

  if (options.proto === 'https') {
    this.authorized = true;
  }

  this.writable = true;
  this.readable = true;
  this.destroyed = false;

  this.setNoDelay = noop;
  this.setKeepAlive = noop;
  this.resume = noop;

  // totalDelay that has already been applied to the current
  // request/connection, timeout error will be generated if
  // it is timed-out.
  this.totalDelayMs = 0;
  // Maximum allowed delay. Null means unlimited.
  this.timeoutMs = null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.nock.socket.super_"></a>[function <span class="apidocSignatureSpan">nock.socket.</span>super_ ()](#apidoc.element.nock.socket.super_)
- description and source-code
```javascript
function EventEmitter() {
  EventEmitter.init.call(this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.nock.socket.prototype"></a>[module nock.socket.prototype](#apidoc.module.nock.socket.prototype)

#### <a name="apidoc.element.nock.socket.prototype.applyDelay"></a>[function <span class="apidocSignatureSpan">nock.socket.prototype.</span>applyDelay (delayMs)](#apidoc.element.nock.socket.prototype.applyDelay)
- description and source-code
```javascript
function applyDelay(delayMs) {
  this.totalDelayMs += delayMs;

  if (this.timeoutMs && this.totalDelayMs > this.timeoutMs) {
    debug('socket timeout');
    if (this.timeoutFunction) {
      this.timeoutFunction();
    }
    else {
      this.emit('timeout');
    }
  }

}
```
- example usage
```shell
...
      process.nextTick(respond);

      function respond() {

if (aborted) { return; }

if (interceptor.socketDelayInMs && interceptor.socketDelayInMs > 0) {
  req.socket.applyDelay(interceptor.socketDelayInMs);
}

if (interceptor.delayConnectionInMs && interceptor.delayConnectionInMs > 0) {
  setTimeout(_respond, interceptor.delayConnectionInMs);
} else {
  _respond();
}
...
```

#### <a name="apidoc.element.nock.socket.prototype.destroy"></a>[function <span class="apidocSignatureSpan">nock.socket.prototype.</span>destroy ()](#apidoc.element.nock.socket.prototype.destroy)
- description and source-code
```javascript
function destroy() {
  this.destroyed = true;
  this.readable = this.writable = false;
}
```
- example usage
```shell
...
  if (!ended) {
    end();
  }
  var err = new Error();
  err.code = 'aborted';
  response.emit('close', err);

  req.socket.destroy();

  req.emit('abort');

  var connResetError = new Error('socket hang up');
  connResetError.code = 'ECONNRESET';
  emitError(connResetError);
};
...
```

#### <a name="apidoc.element.nock.socket.prototype.getPeerCertificate"></a>[function <span class="apidocSignatureSpan">nock.socket.prototype.</span>getPeerCertificate ()](#apidoc.element.nock.socket.prototype.getPeerCertificate)
- description and source-code
```javascript
function getPeerCertificate() {
  return new Buffer((Math.random() * 10000 + Date.now()).toString()).toString('base64');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.nock.socket.prototype.setTimeout"></a>[function <span class="apidocSignatureSpan">nock.socket.prototype.</span>setTimeout (timeoutMs, fn)](#apidoc.element.nock.socket.prototype.setTimeout)
- description and source-code
```javascript
function setTimeout(timeoutMs, fn) {
  this.timeoutMs = timeoutMs;
  this.timeoutFunction = fn;
}
```
- example usage
```shell
...

To test a request like the following:

'''js
req = http.request('http://my.server.com', function(res) {
  ...
});
req.setTimeout(1000, function() {
  req.abort();
});
req.end();
'''

NOTE: the timeout will be fired immediately, and will not leave the simulated connection idle for the specified period of time.
...
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
