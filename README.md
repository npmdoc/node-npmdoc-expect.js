# api documentation for  [expect.js (v0.3.1)](https://github.com/LearnBoost/expect.js)  [![npm package](https://img.shields.io/npm/v/npmdoc-expect.js.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-expect.js) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-expect.js.svg)](https://travis-ci.org/npmdoc/node-npmdoc-expect.js)
#### BDD style assertions for node and the browser.

[![NPM](https://nodei.co/npm/expect.js.png?downloads=true)](https://www.npmjs.com/package/expect.js)

[![apidoc](https://npmdoc.github.io/node-npmdoc-expect.js/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-expect.js_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-expect.js/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-expect.js/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-expect.js/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/LearnBoost/expect.js/issues"
    },
    "dependencies": {},
    "description": "BDD style assertions for node and the browser.",
    "devDependencies": {
        "mocha": "*",
        "serve": "*"
    },
    "directories": {},
    "dist": {
        "shasum": "b0a59a0d2eff5437544ebf0ceaa6015841d09b5b",
        "tarball": "https://registry.npmjs.org/expect.js/-/expect.js-0.3.1.tgz"
    },
    "homepage": "https://github.com/LearnBoost/expect.js",
    "maintainers": [
        {
            "name": "rauchg",
            "email": "rauchg@gmail.com"
        }
    ],
    "name": "expect.js",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/LearnBoost/expect.js.git"
    },
    "version": "0.3.1"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module expect.js](#apidoc.module.expect.js)
1.  [function <span class="apidocSignatureSpan">expect.js.</span>Assertion (obj, flag, parent)](#apidoc.element.expect.js.Assertion)
1.  [function <span class="apidocSignatureSpan">expect.js.</span>eql (actual, expected)](#apidoc.element.expect.js.eql)
1.  [function <span class="apidocSignatureSpan">expect.js.</span>js.Assertion (obj, flag, parent)](#apidoc.element.expect.js.js.Assertion)
1.  [function <span class="apidocSignatureSpan">expect.js.</span>stringify (obj, showHidden, depth)](#apidoc.element.expect.js.stringify)
1.  object <span class="apidocSignatureSpan">expect.js.</span>js.Assertion.prototype
1.  string <span class="apidocSignatureSpan">expect.js.</span>version

#### [module expect.js.Assertion](#apidoc.module.expect.js.Assertion)
1.  [function <span class="apidocSignatureSpan">expect.js.</span>Assertion (obj, flag, parent)](#apidoc.element.expect.js.Assertion.Assertion)

#### [module expect.js.Assertion.prototype](#apidoc.module.expect.js.Assertion.prototype)
1.  [function <span class="apidocSignatureSpan">expect.js.Assertion.prototype.</span>a (type)](#apidoc.element.expect.js.Assertion.prototype.a)
1.  [function <span class="apidocSignatureSpan">expect.js.Assertion.prototype.</span>above (n)](#apidoc.element.expect.js.Assertion.prototype.above)
1.  [function <span class="apidocSignatureSpan">expect.js.Assertion.prototype.</span>an (type)](#apidoc.element.expect.js.Assertion.prototype.an)
1.  [function <span class="apidocSignatureSpan">expect.js.Assertion.prototype.</span>assert (truth, msg, error, expected)](#apidoc.element.expect.js.Assertion.prototype.assert)
1.  [function <span class="apidocSignatureSpan">expect.js.Assertion.prototype.</span>be (obj)](#apidoc.element.expect.js.Assertion.prototype.be)
1.  [function <span class="apidocSignatureSpan">expect.js.Assertion.prototype.</span>below (n)](#apidoc.element.expect.js.Assertion.prototype.below)
1.  [function <span class="apidocSignatureSpan">expect.js.Assertion.prototype.</span>contain (obj)](#apidoc.element.expect.js.Assertion.prototype.contain)
1.  [function <span class="apidocSignatureSpan">expect.js.Assertion.prototype.</span>empty ()](#apidoc.element.expect.js.Assertion.prototype.empty)
1.  [function <span class="apidocSignatureSpan">expect.js.Assertion.prototype.</span>eql (obj)](#apidoc.element.expect.js.Assertion.prototype.eql)
1.  [function <span class="apidocSignatureSpan">expect.js.Assertion.prototype.</span>equal (obj)](#apidoc.element.expect.js.Assertion.prototype.equal)
1.  [function <span class="apidocSignatureSpan">expect.js.Assertion.prototype.</span>fail (msg)](#apidoc.element.expect.js.Assertion.prototype.fail)
1.  [function <span class="apidocSignatureSpan">expect.js.Assertion.prototype.</span>greaterThan (n)](#apidoc.element.expect.js.Assertion.prototype.greaterThan)
1.  [function <span class="apidocSignatureSpan">expect.js.Assertion.prototype.</span>key ($keys)](#apidoc.element.expect.js.Assertion.prototype.key)
1.  [function <span class="apidocSignatureSpan">expect.js.Assertion.prototype.</span>keys ($keys)](#apidoc.element.expect.js.Assertion.prototype.keys)
1.  [function <span class="apidocSignatureSpan">expect.js.Assertion.prototype.</span>length (n)](#apidoc.element.expect.js.Assertion.prototype.length)
1.  [function <span class="apidocSignatureSpan">expect.js.Assertion.prototype.</span>lessThan (n)](#apidoc.element.expect.js.Assertion.prototype.lessThan)
1.  [function <span class="apidocSignatureSpan">expect.js.Assertion.prototype.</span>match (regexp)](#apidoc.element.expect.js.Assertion.prototype.match)
1.  [function <span class="apidocSignatureSpan">expect.js.Assertion.prototype.</span>ok ()](#apidoc.element.expect.js.Assertion.prototype.ok)
1.  [function <span class="apidocSignatureSpan">expect.js.Assertion.prototype.</span>property (name, val)](#apidoc.element.expect.js.Assertion.prototype.property)
1.  [function <span class="apidocSignatureSpan">expect.js.Assertion.prototype.</span>string (obj)](#apidoc.element.expect.js.Assertion.prototype.string)
1.  [function <span class="apidocSignatureSpan">expect.js.Assertion.prototype.</span>throwError (fn)](#apidoc.element.expect.js.Assertion.prototype.throwError)
1.  [function <span class="apidocSignatureSpan">expect.js.Assertion.prototype.</span>throwException (fn)](#apidoc.element.expect.js.Assertion.prototype.throwException)
1.  [function <span class="apidocSignatureSpan">expect.js.Assertion.prototype.</span>withArgs ()](#apidoc.element.expect.js.Assertion.prototype.withArgs)
1.  [function <span class="apidocSignatureSpan">expect.js.Assertion.prototype.</span>within (start, finish)](#apidoc.element.expect.js.Assertion.prototype.within)



# <a name="apidoc.module.expect.js"></a>[module expect.js](#apidoc.module.expect.js)

#### <a name="apidoc.element.expect.js.Assertion"></a>[function <span class="apidocSignatureSpan">expect.js.</span>Assertion (obj, flag, parent)](#apidoc.element.expect.js.Assertion)
- description and source-code
```javascript
function Assertion(obj, flag, parent) {
  this.obj = obj;
  this.flags = {};

  if (undefined != parent) {
    this.flags[flag] = true;

    for (var i in parent.flags) {
      if (parent.flags.hasOwnProperty(i)) {
        this.flags[i] = true;
      }
    }
  }

  var $flags = flag ? flags[flag] : keys(flags)
    , self = this;

  if ($flags) {
    for (var i = 0, l = $flags.length; i < l; i++) {
      // avoid recursion
      if (this.flags[$flags[i]]) continue;

      var name = $flags[i]
        , assertion = new Assertion(this.obj, name, this)

      if ('function' == typeof Assertion.prototype[name]) {
        // clone the function, make sure we dont touch the prot reference
        var old = this[name];
        this[name] = function () {
          return old.apply(self, arguments);
        };

        for (var fn in Assertion.prototype) {
          if (Assertion.prototype.hasOwnProperty(fn) && fn != name) {
            this[name][fn] = bind(assertion[fn], assertion);
          }
        }
      } else {
        this[name] = assertion;
      }
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.expect.js.eql"></a>[function <span class="apidocSignatureSpan">expect.js.</span>eql (actual, expected)](#apidoc.element.expect.js.eql)
- description and source-code
```javascript
function eql(actual, expected) {
  // 7.1. All identical values are equivalent, as determined by ===.
  if (actual === expected) {
    return true;
  } else if ('undefined' != typeof Buffer
    && Buffer.isBuffer(actual) && Buffer.isBuffer(expected)) {
    if (actual.length != expected.length) return false;

    for (var i = 0; i < actual.length; i++) {
      if (actual[i] !== expected[i]) return false;
    }

    return true;

    // 7.2. If the expected value is a Date object, the actual value is
    // equivalent if it is also a Date object that refers to the same time.
  } else if (actual instanceof Date && expected instanceof Date) {
    return actual.getTime() === expected.getTime();

    // 7.3. Other pairs that do not both pass typeof value == "object",
    // equivalence is determined by ==.
  } else if (typeof actual != 'object' && typeof expected != 'object') {
    return actual == expected;
  // If both are regular expression use the special 'regExpEquiv' method
  // to determine equivalence.
  } else if (isRegExp(actual) && isRegExp(expected)) {
    return regExpEquiv(actual, expected);
  // 7.4. For all other Object pairs, including Array objects, equivalence is
  // determined by having the same number of owned properties (as verified
  // with Object.prototype.hasOwnProperty.call), the same set of keys
  // (although not necessarily the same order), equivalent values for every
  // corresponding key, and an identical "prototype" property. Note: this
  // accounts for both named and indexed properties on Arrays.
  } else {
    return objEquiv(actual, expected);
  }
}
```
- example usage
```shell
...
# Expect

Minimalistic BDD assertion toolkit based on
[should.js](http://github.com/visionmedia/should.js)

'''js
expect(window.r).to.be(undefined);
expect({ a: 'b' }).to.eql({ a: 'b' })
expect(5).to.be.a('number');
expect([]).to.be.an('array');
expect(window).not.to.be.an(Image);
'''

## Features
...
```

#### <a name="apidoc.element.expect.js.js.Assertion"></a>[function <span class="apidocSignatureSpan">expect.js.</span>js.Assertion (obj, flag, parent)](#apidoc.element.expect.js.js.Assertion)
- description and source-code
```javascript
function Assertion(obj, flag, parent) {
  this.obj = obj;
  this.flags = {};

  if (undefined != parent) {
    this.flags[flag] = true;

    for (var i in parent.flags) {
      if (parent.flags.hasOwnProperty(i)) {
        this.flags[i] = true;
      }
    }
  }

  var $flags = flag ? flags[flag] : keys(flags)
    , self = this;

  if ($flags) {
    for (var i = 0, l = $flags.length; i < l; i++) {
      // avoid recursion
      if (this.flags[$flags[i]]) continue;

      var name = $flags[i]
        , assertion = new Assertion(this.obj, name, this)

      if ('function' == typeof Assertion.prototype[name]) {
        // clone the function, make sure we dont touch the prot reference
        var old = this[name];
        this[name] = function () {
          return old.apply(self, arguments);
        };

        for (var fn in Assertion.prototype) {
          if (Assertion.prototype.hasOwnProperty(fn) && fn != name) {
            this[name][fn] = bind(assertion[fn], assertion);
          }
        }
      } else {
        this[name] = assertion;
      }
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.expect.js.stringify"></a>[function <span class="apidocSignatureSpan">expect.js.</span>stringify (obj, showHidden, depth)](#apidoc.element.expect.js.stringify)
- description and source-code
```javascript
function i(obj, showHidden, depth) {
  var seen = [];

  function stylize (str) {
    return str;
  }

  function format (value, recurseTimes) {
    // Provide a hook for user-specified inspect functions.
    // Check that value is an object with an inspect function on it
    if (value && typeof value.inspect === 'function' &&
        // Filter out the util module, it's inspect function is special
        value !== exports &&
        // Also filter out any prototype objects using the circular check.
        !(value.constructor && value.constructor.prototype === value)) {
      return value.inspect(recurseTimes);
    }

    // Primitive types cannot have properties
    switch (typeof value) {
      case 'undefined':
        return stylize('undefined', 'undefined');

      case 'string':
        var simple = '\'' + json.stringify(value).replace(/^"|"$/g, '')
                                                 .replace(/'/g, "\\'")
                                                 .replace(/\\"/g, '"') + '\'';
        return stylize(simple, 'string');

      case 'number':
        return stylize('' + value, 'number');

      case 'boolean':
        return stylize('' + value, 'boolean');
    }
    // For some reason typeof null is "object", so special case here.
    if (value === null) {
      return stylize('null', 'null');
    }

    if (isDOMElement(value)) {
      return getOuterHTML(value);
    }

    // Look up the keys of the object.
    var visible_keys = keys(value);
    var $keys = showHidden ? Object.getOwnPropertyNames(value) : visible_keys;

    // Functions without properties can be shortcutted.
    if (typeof value === 'function' && $keys.length === 0) {
      if (isRegExp(value)) {
        return stylize('' + value, 'regexp');
      } else {
        var name = value.name ? ': ' + value.name : '';
        return stylize('[Function' + name + ']', 'special');
      }
    }

    // Dates without properties can be shortcutted
    if (isDate(value) && $keys.length === 0) {
      return stylize(value.toUTCString(), 'date');
    }

    // Error objects can be shortcutted
    if (value instanceof Error) {
      return stylize("["+value.toString()+"]", 'Error');
    }

    var base, type, braces;
    // Determine the object type
    if (isArray(value)) {
      type = 'Array';
      braces = ['[', ']'];
    } else {
      type = 'Object';
      braces = ['{', '}'];
    }

    // Make functions say that they are functions
    if (typeof value === 'function') {
      var n = value.name ? ': ' + value.name : '';
      base = (isRegExp(value)) ? ' ' + value : ' [Function' + n + ']';
    } else {
      base = '';
    }

    // Make dates with properties first say the date
    if (isDate(value)) {
      base = ' ' + value.toUTCString();
    }

    if ($keys.length === 0) {
      return braces[0] + base + braces[1];
    }

    if (recurseTimes < 0) {
      if (isRegExp(value)) {
        return stylize('' + value, 'regexp');
      } else {
        return stylize('[Object]', 'special');
      }
    }

    seen.push(value);

    var output = map($keys, function (key) {
      var name, str;
      if (value.__lookupGetter__) {
        if (value.__lookupGetter__(key)) {
          if (value.__lookupSetter__(key)) {
            str = stylize('[Getter/Setter]', 'special');
          } else {
            str = stylize('[Getter]', 'special');
          }
        } else {
          if (value.__lookupSetter__(key)) {
            str = stylize('[Setter]', 'special');
          }
        }
      }
      if (indexOf(visible_keys, key) < 0) {
        name = '[' + key + ']';
      }
      if (!str) {
        if (indexOf(seen, value[key]) < 0) {
          if (recurseTimes === null) {
            str = format(value[key]);
          } else {
            str = format(value[key], recurseTimes - 1);
          }
          if (str.indexOf('\n') > -1) {
            if (isArray(value)) {
              str = map(str.split('\n'), function (line) {
                return '  ' + line;
              }).join('\n').substr(2);
            } else { ...
```
- example usage
```shell
...

      // Primitive types cannot have properties
      switch (typeof value) {
case 'undefined':
  return stylize('undefined', 'undefined');

case 'string':
  var simple = '\'' + json.stringify(value).replace(/^"|"$/g, '')
                                           .replace(/'/g, "\\'")
                                           .replace(/\\"/g, '"') + '\'';
  return stylize(simple, 'string');

case 'number':
  return stylize('' + value, 'number');
...
```



# <a name="apidoc.module.expect.js.Assertion"></a>[module expect.js.Assertion](#apidoc.module.expect.js.Assertion)

#### <a name="apidoc.element.expect.js.Assertion.Assertion"></a>[function <span class="apidocSignatureSpan">expect.js.</span>Assertion (obj, flag, parent)](#apidoc.element.expect.js.Assertion.Assertion)
- description and source-code
```javascript
function Assertion(obj, flag, parent) {
  this.obj = obj;
  this.flags = {};

  if (undefined != parent) {
    this.flags[flag] = true;

    for (var i in parent.flags) {
      if (parent.flags.hasOwnProperty(i)) {
        this.flags[i] = true;
      }
    }
  }

  var $flags = flag ? flags[flag] : keys(flags)
    , self = this;

  if ($flags) {
    for (var i = 0, l = $flags.length; i < l; i++) {
      // avoid recursion
      if (this.flags[$flags[i]]) continue;

      var name = $flags[i]
        , assertion = new Assertion(this.obj, name, this)

      if ('function' == typeof Assertion.prototype[name]) {
        // clone the function, make sure we dont touch the prot reference
        var old = this[name];
        this[name] = function () {
          return old.apply(self, arguments);
        };

        for (var fn in Assertion.prototype) {
          if (Assertion.prototype.hasOwnProperty(fn) && fn != name) {
            this[name][fn] = bind(assertion[fn], assertion);
          }
        }
      } else {
        this[name] = assertion;
      }
    }
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.expect.js.Assertion.prototype"></a>[module expect.js.Assertion.prototype](#apidoc.module.expect.js.Assertion.prototype)

#### <a name="apidoc.element.expect.js.Assertion.prototype.a"></a>[function <span class="apidocSignatureSpan">expect.js.Assertion.prototype.</span>a (type)](#apidoc.element.expect.js.Assertion.prototype.a)
- description and source-code
```javascript
a = function (type) {
  if ('string' == typeof type) {
    // proper english in error msg
    var n = /^[aeiou]/.test(type) ? 'n' : '';

    // typeof with support for 'array'
    this.assert(
        'array' == type ? isArray(this.obj) :
          'regexp' == type ? isRegExp(this.obj) :
            'object' == type
              ? 'object' == typeof this.obj && null !== this.obj
              : type == typeof this.obj
      , function(){ return 'expected ' + i(this.obj) + ' to be a' + n + ' ' + type }
      , function(){ return 'expected ' + i(this.obj) + ' not to be a' + n + ' ' + type });
  } else {
    // instanceof
    var name = type.name || 'supplied constructor';
    this.assert(
        this.obj instanceof type
      , function(){ return 'expected ' + i(this.obj) + ' to be an instance of ' + name }
      , function(){ return 'expected ' + i(this.obj) + ' not to be an instance of ' + name });
  }

  return this;
}
```
- example usage
```shell
...

Minimalistic BDD assertion toolkit based on
[should.js](http://github.com/visionmedia/should.js)

'''js
expect(window.r).to.be(undefined);
expect({ a: 'b' }).to.eql({ a: 'b' })
expect(5).to.be.a('number');
expect([]).to.be.an('array');
expect(window).not.to.be.an(Image);
'''

## Features

- Cross-browser: works on IE6+, Firefox, Safari, Chrome, Opera.
...
```

#### <a name="apidoc.element.expect.js.Assertion.prototype.above"></a>[function <span class="apidocSignatureSpan">expect.js.Assertion.prototype.</span>above (n)](#apidoc.element.expect.js.Assertion.prototype.above)
- description and source-code
```javascript
above = function (n) {
  this.assert(
      this.obj > n
    , function(){ return 'expected ' + i(this.obj) + ' to be above ' + n }
    , function(){ return 'expected ' + i(this.obj) + ' to be below ' + n });
  return this;
}
```
- example usage
```shell
...
'''js
expect(1).to.be.within(0, Infinity);
'''

**greaterThan**/**above**: asserts '>'

'''js
expect(3).to.be.above(0);
expect(5).to.be.greaterThan(3);
'''

**lessThan**/**below**: asserts '<'

'''js
expect(0).to.be.below(3);
...
```

#### <a name="apidoc.element.expect.js.Assertion.prototype.an"></a>[function <span class="apidocSignatureSpan">expect.js.Assertion.prototype.</span>an (type)](#apidoc.element.expect.js.Assertion.prototype.an)
- description and source-code
```javascript
an = function (type) {
  if ('string' == typeof type) {
    // proper english in error msg
    var n = /^[aeiou]/.test(type) ? 'n' : '';

    // typeof with support for 'array'
    this.assert(
        'array' == type ? isArray(this.obj) :
          'regexp' == type ? isRegExp(this.obj) :
            'object' == type
              ? 'object' == typeof this.obj && null !== this.obj
              : type == typeof this.obj
      , function(){ return 'expected ' + i(this.obj) + ' to be a' + n + ' ' + type }
      , function(){ return 'expected ' + i(this.obj) + ' not to be a' + n + ' ' + type });
  } else {
    // instanceof
    var name = type.name || 'supplied constructor';
    this.assert(
        this.obj instanceof type
      , function(){ return 'expected ' + i(this.obj) + ' to be an instance of ' + name }
      , function(){ return 'expected ' + i(this.obj) + ' not to be an instance of ' + name });
  }

  return this;
}
```
- example usage
```shell
...
Minimalistic BDD assertion toolkit based on
[should.js](http://github.com/visionmedia/should.js)

'''js
expect(window.r).to.be(undefined);
expect({ a: 'b' }).to.eql({ a: 'b' })
expect(5).to.be.a('number');
expect([]).to.be.an('array');
expect(window).not.to.be.an(Image);
'''

## Features

- Cross-browser: works on IE6+, Firefox, Safari, Chrome, Opera.
- Compatible with all test frameworks.
...
```

#### <a name="apidoc.element.expect.js.Assertion.prototype.assert"></a>[function <span class="apidocSignatureSpan">expect.js.Assertion.prototype.</span>assert (truth, msg, error, expected)](#apidoc.element.expect.js.Assertion.prototype.assert)
- description and source-code
```javascript
assert = function (truth, msg, error, expected) {
  var msg = this.flags.not ? error : msg
    , ok = this.flags.not ? !truth : truth
    , err;

  if (!ok) {
    err = new Error(msg.call(this));
    if (arguments.length > 3) {
      err.actual = this.obj;
      err.expected = expected;
      err.showDiff = true;
    }
    throw err;
  }

  this.and = new Assertion(this.obj);
}
```
- example usage
```shell
...
/**
 * Check if the value is truthy
 *
 * @api public
 */

Assertion.prototype.ok = function () {
  this.assert(
      !!this.obj
    , function(){ return 'expected ' + i(this.obj) + ' to be truthy' }
    , function(){ return 'expected ' + i(this.obj) + ' to be falsy' });
};

/**
 * Creates an anonymous function which calls fn with arguments.
...
```

#### <a name="apidoc.element.expect.js.Assertion.prototype.be"></a>[function <span class="apidocSignatureSpan">expect.js.Assertion.prototype.</span>be (obj)](#apidoc.element.expect.js.Assertion.prototype.be)
- description and source-code
```javascript
be = function (obj) {
  this.assert(
      obj === this.obj
    , function(){ return 'expected ' + i(this.obj) + ' to equal ' + i(obj) }
    , function(){ return 'expected ' + i(this.obj) + ' to not equal ' + i(obj) });
  return this;
}
```
- example usage
```shell
...

# Expect

Minimalistic BDD assertion toolkit based on
[should.js](http://github.com/visionmedia/should.js)

'''js
expect(window.r).to.be(undefined);
expect({ a: 'b' }).to.eql({ a: 'b' })
expect(5).to.be.a('number');
expect([]).to.be.an('array');
expect(window).not.to.be.an(Image);
'''

## Features
...
```

#### <a name="apidoc.element.expect.js.Assertion.prototype.below"></a>[function <span class="apidocSignatureSpan">expect.js.Assertion.prototype.</span>below (n)](#apidoc.element.expect.js.Assertion.prototype.below)
- description and source-code
```javascript
below = function (n) {
  this.assert(
      this.obj < n
    , function(){ return 'expected ' + i(this.obj) + ' to be below ' + n }
    , function(){ return 'expected ' + i(this.obj) + ' to be above ' + n });
  return this;
}
```
- example usage
```shell
...
expect(3).to.be.above(0);
expect(5).to.be.greaterThan(3);
'''

**lessThan**/**below**: asserts '<'

'''js
expect(0).to.be.below(3);
expect(1).to.be.lessThan(3);
'''

**fail**: explicitly forces failure.

'''js
expect().fail()
...
```

#### <a name="apidoc.element.expect.js.Assertion.prototype.contain"></a>[function <span class="apidocSignatureSpan">expect.js.Assertion.prototype.</span>contain (obj)](#apidoc.element.expect.js.Assertion.prototype.contain)
- description and source-code
```javascript
contain = function (obj) {
  if ('string' == typeof this.obj) {
    this.assert(
        ~this.obj.indexOf(obj)
      , function(){ return 'expected ' + i(this.obj) + ' to contain ' + i(obj) }
      , function(){ return 'expected ' + i(this.obj) + ' to not contain ' + i(obj) });
  } else {
    this.assert(
        ~indexOf(this.obj, obj)
      , function(){ return 'expected ' + i(this.obj) + ' to contain ' + i(obj) }
      , function(){ return 'expected ' + i(this.obj) + ' to not contain ' + i(obj) });
  }
  return this;
}
```
- example usage
```shell
...
'''js
expect(program.version).to.match(/[0-9]+\.[0-9]+\.[0-9]+/);
'''

**contain**: asserts indexOf for an array or string

'''js
expect([1, 2]).to.contain(1);
expect('hello world').to.contain('world');
'''

**length**: asserts array '.length'

'''js
expect([]).to.have.length(0);
...
```

#### <a name="apidoc.element.expect.js.Assertion.prototype.empty"></a>[function <span class="apidocSignatureSpan">expect.js.Assertion.prototype.</span>empty ()](#apidoc.element.expect.js.Assertion.prototype.empty)
- description and source-code
```javascript
empty = function () {
  var expectation;

  if ('object' == typeof this.obj && null !== this.obj && !isArray(this.obj)) {
    if ('number' == typeof this.obj.length) {
      expectation = !this.obj.length;
    } else {
      expectation = !keys(this.obj).length;
    }
  } else {
    if ('string' != typeof this.obj) {
      expect(this.obj).to.be.an('object');
    }

    expect(this.obj).to.have.property('length');
    expectation = !this.obj.length;
  }

  this.assert(
      expectation
    , function(){ return 'expected ' + i(this.obj) + ' to be empty' }
    , function(){ return 'expected ' + i(this.obj) + ' to not be empty' });
  return this;
}
```
- example usage
```shell
...
expect([]).to.have.length(0);
expect([1,2,3]).to.have.length(3);
'''

**empty**: asserts that an array is empty or not

'''js
expect([]).to.be.empty();
expect({}).to.be.empty();
expect({ length: 0, duck: 'typing' }).to.be.empty();
expect({ my: 'object' }).to.not.be.empty();
expect([1,2,3]).to.not.be.empty();
'''

**property**: asserts presence of an own property (and value optionally)
...
```

#### <a name="apidoc.element.expect.js.Assertion.prototype.eql"></a>[function <span class="apidocSignatureSpan">expect.js.Assertion.prototype.</span>eql (obj)](#apidoc.element.expect.js.Assertion.prototype.eql)
- description and source-code
```javascript
eql = function (obj) {
  this.assert(
      expect.eql(this.obj, obj)
    , function(){ return 'expected ' + i(this.obj) + ' to sort of equal ' + i(obj) }
    , function(){ return 'expected ' + i(this.obj) + ' to sort of not equal ' + i(obj) }
    , obj);
  return this;
}
```
- example usage
```shell
...
# Expect

Minimalistic BDD assertion toolkit based on
[should.js](http://github.com/visionmedia/should.js)

'''js
expect(window.r).to.be(undefined);
expect({ a: 'b' }).to.eql({ a: 'b' })
expect(5).to.be.a('number');
expect([]).to.be.an('array');
expect(window).not.to.be.an(Image);
'''

## Features
...
```

#### <a name="apidoc.element.expect.js.Assertion.prototype.equal"></a>[function <span class="apidocSignatureSpan">expect.js.Assertion.prototype.</span>equal (obj)](#apidoc.element.expect.js.Assertion.prototype.equal)
- description and source-code
```javascript
equal = function (obj) {
  this.assert(
      obj === this.obj
    , function(){ return 'expected ' + i(this.obj) + ' to equal ' + i(obj) }
    , function(){ return 'expected ' + i(this.obj) + ' to not equal ' + i(obj) });
  return this;
}
```
- example usage
```shell
...
expect(0).to.not.be.ok();
'''

**be** / **equal**: asserts '===' equality

'''js
expect(1).to.be(1)
expect(NaN).not.to.equal(NaN);
expect(1).not.to.be(true)
expect('1').to.not.be(1);
'''

**eql**: asserts loose equality that works with objects

'''js
...
```

#### <a name="apidoc.element.expect.js.Assertion.prototype.fail"></a>[function <span class="apidocSignatureSpan">expect.js.Assertion.prototype.</span>fail (msg)](#apidoc.element.expect.js.Assertion.prototype.fail)
- description and source-code
```javascript
fail = function (msg) {
  var error = function() { return msg || "explicit failure"; }
  this.assert(false, error, error);
  return this;
}
```
- example usage
```shell
...
expect(0).to.be.below(3);
expect(1).to.be.lessThan(3);
'''

**fail**: explicitly forces failure.

'''js
expect().fail()
expect().fail("Custom failure message")
'''

## Using with a test framework

For example, if you create a test suite with
[mocha](http://github.com/visionmedia/mocha).
...
```

#### <a name="apidoc.element.expect.js.Assertion.prototype.greaterThan"></a>[function <span class="apidocSignatureSpan">expect.js.Assertion.prototype.</span>greaterThan (n)](#apidoc.element.expect.js.Assertion.prototype.greaterThan)
- description and source-code
```javascript
greaterThan = function (n) {
  this.assert(
      this.obj > n
    , function(){ return 'expected ' + i(this.obj) + ' to be above ' + n }
    , function(){ return 'expected ' + i(this.obj) + ' to be below ' + n });
  return this;
}
```
- example usage
```shell
...
expect(1).to.be.within(0, Infinity);
'''

**greaterThan**/**above**: asserts '>'

'''js
expect(3).to.be.above(0);
expect(5).to.be.greaterThan(3);
'''

**lessThan**/**below**: asserts '<'

'''js
expect(0).to.be.below(3);
expect(1).to.be.lessThan(3);
...
```

#### <a name="apidoc.element.expect.js.Assertion.prototype.key"></a>[function <span class="apidocSignatureSpan">expect.js.Assertion.prototype.</span>key ($keys)](#apidoc.element.expect.js.Assertion.prototype.key)
- description and source-code
```javascript
key = function ($keys) {
  var str
    , ok = true;

  $keys = isArray($keys)
    ? $keys
    : Array.prototype.slice.call(arguments);

  if (!$keys.length) throw new Error('keys required');

  var actual = keys(this.obj)
    , len = $keys.length;

  // Inclusion
  ok = every($keys, function (key) {
    return ~indexOf(actual, key);
  });

  // Strict
  if (!this.flags.not && this.flags.only) {
    ok = ok && $keys.length == actual.length;
  }

  // Key string
  if (len > 1) {
    $keys = map($keys, function (key) {
      return i(key);
    });
    var last = $keys.pop();
    str = $keys.join(', ') + ', and ' + last;
  } else {
    str = i($keys[0]);
  }

  // Form
  str = (len > 1 ? 'keys ' : 'key ') + str;

  // Have / include
  str = (!this.flags.only ? 'include ' : 'only have ') + str;

  // Assertion
  this.assert(
      ok
    , function(){ return 'expected ' + i(this.obj) + ' to ' + str }
    , function(){ return 'expected ' + i(this.obj) + ' to not ' + str });

  return this;
}
```
- example usage
```shell
...
expect(window).to.have.property('expect', expect)
expect({a: 'b'}).to.have.property('a');
'''

**key**/**keys**: asserts the presence of a key. Supports the 'only' modifier

'''js
expect({ a: 'b' }).to.have.key('a');
expect({ a: 'b', c: 'd' }).to.only.have.keys('a', 'c');
expect({ a: 'b', c: 'd' }).to.only.have.keys(['a', 'c']);
expect({ a: 'b', c: 'd' }).to.not.only.have.key('a');
'''

**throwException**/**throwError**: asserts that the 'Function' throws or not when called
...
```

#### <a name="apidoc.element.expect.js.Assertion.prototype.keys"></a>[function <span class="apidocSignatureSpan">expect.js.Assertion.prototype.</span>keys ($keys)](#apidoc.element.expect.js.Assertion.prototype.keys)
- description and source-code
```javascript
keys = function ($keys) {
  var str
    , ok = true;

  $keys = isArray($keys)
    ? $keys
    : Array.prototype.slice.call(arguments);

  if (!$keys.length) throw new Error('keys required');

  var actual = keys(this.obj)
    , len = $keys.length;

  // Inclusion
  ok = every($keys, function (key) {
    return ~indexOf(actual, key);
  });

  // Strict
  if (!this.flags.not && this.flags.only) {
    ok = ok && $keys.length == actual.length;
  }

  // Key string
  if (len > 1) {
    $keys = map($keys, function (key) {
      return i(key);
    });
    var last = $keys.pop();
    str = $keys.join(', ') + ', and ' + last;
  } else {
    str = i($keys[0]);
  }

  // Form
  str = (len > 1 ? 'keys ' : 'key ') + str;

  // Have / include
  str = (!this.flags.only ? 'include ' : 'only have ') + str;

  // Assertion
  this.assert(
      ok
    , function(){ return 'expected ' + i(this.obj) + ' to ' + str }
    , function(){ return 'expected ' + i(this.obj) + ' to not ' + str });

  return this;
}
```
- example usage
```shell
...
expect({a: 'b'}).to.have.property('a');
'''

**key**/**keys**: asserts the presence of a key. Supports the 'only' modifier

'''js
expect({ a: 'b' }).to.have.key('a');
expect({ a: 'b', c: 'd' }).to.only.have.keys('a', 'c');
expect({ a: 'b', c: 'd' }).to.only.have.keys(['a', 'c']);
expect({ a: 'b', c: 'd' }).to.not.only.have.key('a');
'''

**throwException**/**throwError**: asserts that the 'Function' throws or not when called

'''js
...
```

#### <a name="apidoc.element.expect.js.Assertion.prototype.length"></a>[function <span class="apidocSignatureSpan">expect.js.Assertion.prototype.</span>length (n)](#apidoc.element.expect.js.Assertion.prototype.length)
- description and source-code
```javascript
length = function (n) {
  expect(this.obj).to.have.property('length');
  var len = this.obj.length;
  this.assert(
      n == len
    , function(){ return 'expected ' + i(this.obj) + ' to have a length of ' + n + ' but got ' + len }
    , function(){ return 'expected ' + i(this.obj) + ' to not have a length of ' + len });
  return this;
}
```
- example usage
```shell
...
expect([1, 2]).to.contain(1);
expect('hello world').to.contain('world');
'''

**length**: asserts array '.length'

'''js
expect([]).to.have.length(0);
expect([1,2,3]).to.have.length(3);
'''

**empty**: asserts that an array is empty or not

'''js
expect([]).to.be.empty();
...
```

#### <a name="apidoc.element.expect.js.Assertion.prototype.lessThan"></a>[function <span class="apidocSignatureSpan">expect.js.Assertion.prototype.</span>lessThan (n)](#apidoc.element.expect.js.Assertion.prototype.lessThan)
- description and source-code
```javascript
lessThan = function (n) {
  this.assert(
      this.obj < n
    , function(){ return 'expected ' + i(this.obj) + ' to be below ' + n }
    , function(){ return 'expected ' + i(this.obj) + ' to be above ' + n });
  return this;
}
```
- example usage
```shell
...
expect(5).to.be.greaterThan(3);
'''

**lessThan**/**below**: asserts '<'

'''js
expect(0).to.be.below(3);
expect(1).to.be.lessThan(3);
'''

**fail**: explicitly forces failure.

'''js
expect().fail()
expect().fail("Custom failure message")
...
```

#### <a name="apidoc.element.expect.js.Assertion.prototype.match"></a>[function <span class="apidocSignatureSpan">expect.js.Assertion.prototype.</span>match (regexp)](#apidoc.element.expect.js.Assertion.prototype.match)
- description and source-code
```javascript
match = function (regexp) {
  this.assert(
      regexp.exec(this.obj)
    , function(){ return 'expected ' + i(this.obj) + ' to match ' + regexp }
    , function(){ return 'expected ' + i(this.obj) + ' not to match ' + regexp });
  return this;
}
```
- example usage
```shell
...
expect(tobi).to.be.a(Ferret);
expect(person).to.be.a(Mammal);
'''

**match**: asserts 'String' regular expression match

'''js
expect(program.version).to.match(/[0-9]+\.[0-9]+\.[0-9]+/);
'''

**contain**: asserts indexOf for an array or string

'''js
expect([1, 2]).to.contain(1);
expect('hello world').to.contain('world');
...
```

#### <a name="apidoc.element.expect.js.Assertion.prototype.ok"></a>[function <span class="apidocSignatureSpan">expect.js.Assertion.prototype.</span>ok ()](#apidoc.element.expect.js.Assertion.prototype.ok)
- description and source-code
```javascript
ok = function () {
  this.assert(
      !!this.obj
    , function(){ return 'expected ' + i(this.obj) + ' to be truthy' }
    , function(){ return 'expected ' + i(this.obj) + ' to be falsy' });
}
```
- example usage
```shell
...
'''

## API

**ok**: asserts that the value is _truthy_ or not

'''js
expect(1).to.be.ok();
expect(true).to.be.ok();
expect({}).to.be.ok();
expect(0).to.not.be.ok();
'''

**be** / **equal**: asserts '===' equality
...
```

#### <a name="apidoc.element.expect.js.Assertion.prototype.property"></a>[function <span class="apidocSignatureSpan">expect.js.Assertion.prototype.</span>property (name, val)](#apidoc.element.expect.js.Assertion.prototype.property)
- description and source-code
```javascript
property = function (name, val) {
  if (this.flags.own) {
    this.assert(
        Object.prototype.hasOwnProperty.call(this.obj, name)
      , function(){ return 'expected ' + i(this.obj) + ' to have own property ' + i(name) }
      , function(){ return 'expected ' + i(this.obj) + ' to not have own property ' + i(name) });
    return this;
  }

  if (this.flags.not && undefined !== val) {
    if (undefined === this.obj[name]) {
      throw new Error(i(this.obj) + ' has no property ' + i(name));
    }
  } else {
    var hasProp;
    try {
      hasProp = name in this.obj
    } catch (e) {
      hasProp = undefined !== this.obj[name]
    }

    this.assert(
        hasProp
      , function(){ return 'expected ' + i(this.obj) + ' to have a property ' + i(name) }
      , function(){ return 'expected ' + i(this.obj) + ' to not have a property ' + i(name) });
  }

  if (undefined !== val) {
    this.assert(
        val === this.obj[name]
      , function(){ return 'expected ' + i(this.obj) + ' to have a property ' + i(name)
        + ' of ' + i(val) + ', but got ' + i(this.obj[name]) }
      , function(){ return 'expected ' + i(this.obj) + ' to not have a property ' + i(name)
        + ' of ' + i(val) });
  }

  this.obj = this.obj[name];
  return this;
}
```
- example usage
```shell
...
expect({ my: 'object' }).to.not.be.empty();
expect([1,2,3]).to.not.be.empty();
'''

**property**: asserts presence of an own property (and value optionally)

'''js
expect(window).to.have.property('expect')
expect(window).to.have.property('expect', expect)
expect({a: 'b'}).to.have.property('a');
'''

**key**/**keys**: asserts the presence of a key. Supports the 'only' modifier

'''js
...
```

#### <a name="apidoc.element.expect.js.Assertion.prototype.string"></a>[function <span class="apidocSignatureSpan">expect.js.Assertion.prototype.</span>string (obj)](#apidoc.element.expect.js.Assertion.prototype.string)
- description and source-code
```javascript
string = function (obj) {
  if ('string' == typeof this.obj) {
    this.assert(
        ~this.obj.indexOf(obj)
      , function(){ return 'expected ' + i(this.obj) + ' to contain ' + i(obj) }
      , function(){ return 'expected ' + i(this.obj) + ' to not contain ' + i(obj) });
  } else {
    this.assert(
        ~indexOf(this.obj, obj)
      , function(){ return 'expected ' + i(this.obj) + ' to contain ' + i(obj) }
      , function(){ return 'expected ' + i(this.obj) + ' to not contain ' + i(obj) });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.expect.js.Assertion.prototype.throwError"></a>[function <span class="apidocSignatureSpan">expect.js.Assertion.prototype.</span>throwError (fn)](#apidoc.element.expect.js.Assertion.prototype.throwError)
- description and source-code
```javascript
throwError = function (fn) {
  expect(this.obj).to.be.a('function');

  var thrown = false
    , not = this.flags.not;

  try {
    this.obj();
  } catch (e) {
    if (isRegExp(fn)) {
      var subject = 'string' == typeof e ? e : e.message;
      if (not) {
        expect(subject).to.not.match(fn);
      } else {
        expect(subject).to.match(fn);
      }
    } else if ('function' == typeof fn) {
      fn(e);
    }
    thrown = true;
  }

  if (isRegExp(fn) && not) {
    // in the presence of a matcher, ensure the 'not' only applies to
    // the matching.
    this.flags.not = false;
  }

  var name = this.obj.name || 'fn';
  this.assert(
      thrown
    , function(){ return 'expected ' + name + ' to throw an exception' }
    , function(){ return 'expected ' + name + ' not to throw an exception' });
}
```
- example usage
```shell
...
expect({ a: 'b', c: 'd' }).to.only.have.keys(['a', 'c']);
expect({ a: 'b', c: 'd' }).to.not.only.have.key('a');
'''

**throwException**/**throwError**: asserts that the 'Function' throws or not when called

'''js
expect(fn).to.throwError(); // synonym of throwException
expect(fn).to.throwException(function (e) { // get the exception object
  expect(e).to.be.a(SyntaxError);
});
expect(fn).to.throwException(/matches the exception message/);
expect(fn2).to.not.throwException();
'''
...
```

#### <a name="apidoc.element.expect.js.Assertion.prototype.throwException"></a>[function <span class="apidocSignatureSpan">expect.js.Assertion.prototype.</span>throwException (fn)](#apidoc.element.expect.js.Assertion.prototype.throwException)
- description and source-code
```javascript
throwException = function (fn) {
  expect(this.obj).to.be.a('function');

  var thrown = false
    , not = this.flags.not;

  try {
    this.obj();
  } catch (e) {
    if (isRegExp(fn)) {
      var subject = 'string' == typeof e ? e : e.message;
      if (not) {
        expect(subject).to.not.match(fn);
      } else {
        expect(subject).to.match(fn);
      }
    } else if ('function' == typeof fn) {
      fn(e);
    }
    thrown = true;
  }

  if (isRegExp(fn) && not) {
    // in the presence of a matcher, ensure the 'not' only applies to
    // the matching.
    this.flags.not = false;
  }

  var name = this.obj.name || 'fn';
  this.assert(
      thrown
    , function(){ return 'expected ' + name + ' to throw an exception' }
    , function(){ return 'expected ' + name + ' not to throw an exception' });
}
```
- example usage
```shell
...
expect({ a: 'b', c: 'd' }).to.not.only.have.key('a');
'''

**throwException**/**throwError**: asserts that the 'Function' throws or not when called

'''js
expect(fn).to.throwError(); // synonym of throwException
expect(fn).to.throwException(function (e) { // get the exception object
  expect(e).to.be.a(SyntaxError);
});
expect(fn).to.throwException(/matches the exception message/);
expect(fn2).to.not.throwException();
'''

**withArgs**: creates anonymous function to call fn with arguments
...
```

#### <a name="apidoc.element.expect.js.Assertion.prototype.withArgs"></a>[function <span class="apidocSignatureSpan">expect.js.Assertion.prototype.</span>withArgs ()](#apidoc.element.expect.js.Assertion.prototype.withArgs)
- description and source-code
```javascript
withArgs = function () {
  expect(this.obj).to.be.a('function');
  var fn = this.obj;
  var args = Array.prototype.slice.call(arguments);
  return expect(function() { fn.apply(null, args); });
}
```
- example usage
```shell
...
expect(fn).to.throwException(/matches the exception message/);
expect(fn2).to.not.throwException();
'''

**withArgs**: creates anonymous function to call fn with arguments

'''js
expect(fn).withArgs(invalid, arg).to.throwException();
expect(fn).withArgs(valid, arg).to.not.throwException();
'''

**within**: asserts a number within a range

'''js
expect(1).to.be.within(0, Infinity);
...
```

#### <a name="apidoc.element.expect.js.Assertion.prototype.within"></a>[function <span class="apidocSignatureSpan">expect.js.Assertion.prototype.</span>within (start, finish)](#apidoc.element.expect.js.Assertion.prototype.within)
- description and source-code
```javascript
within = function (start, finish) {
  var range = start + '..' + finish;
  this.assert(
      this.obj >= start && this.obj <= finish
    , function(){ return 'expected ' + i(this.obj) + ' to be within ' + range }
    , function(){ return 'expected ' + i(this.obj) + ' to not be within ' + range });
  return this;
}
```
- example usage
```shell
...
expect(fn).withArgs(invalid, arg).to.throwException();
expect(fn).withArgs(valid, arg).to.not.throwException();
'''

**within**: asserts a number within a range

'''js
expect(1).to.be.within(0, Infinity);
'''

**greaterThan**/**above**: asserts '>'

'''js
expect(3).to.be.above(0);
expect(5).to.be.greaterThan(3);
...
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
