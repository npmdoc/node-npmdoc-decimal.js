# api documentation for  [decimal.js (v7.1.2)](https://github.com/MikeMcl/decimal.js#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-decimal.js.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-decimal.js) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-decimal.js.svg)](https://travis-ci.org/npmdoc/node-npmdoc-decimal.js)
#### An arbitrary-precision Decimal type for JavaScript.

[![NPM](https://nodei.co/npm/decimal.js.png?downloads=true)](https://www.npmjs.com/package/decimal.js)

[![apidoc](https://npmdoc.github.io/node-npmdoc-decimal.js/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-decimal.js_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-decimal.js/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-decimal.js/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-decimal.js/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Michael Mclaughlin",
        "email": "M8ch88l@gmail.com"
    },
    "bugs": {
        "url": "https://github.com/MikeMcl/decimal.js/issues"
    },
    "dependencies": {},
    "description": "An arbitrary-precision Decimal type for JavaScript.",
    "devDependencies": {},
    "directories": {},
    "dist": {
        "shasum": "af71a1e2e89a1493bbd456ac746a1a92263a707b",
        "tarball": "https://registry.npmjs.org/decimal.js/-/decimal.js-7.1.2.tgz"
    },
    "gitHead": "85a499eb86959088f69b72cfefc044b927439d6c",
    "homepage": "https://github.com/MikeMcl/decimal.js#readme",
    "keywords": [
        "arbitrary",
        "precision",
        "arithmetic",
        "big",
        "number",
        "decimal",
        "float",
        "biginteger",
        "bigdecimal",
        "bignumber",
        "bigint",
        "bignum"
    ],
    "license": "MIT",
    "main": "decimal.js",
    "maintainers": [
        {
            "name": "mikemcl",
            "email": "M8ch88l@gmail.com"
        }
    ],
    "name": "decimal.js",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/MikeMcl/decimal.js.git"
    },
    "scripts": {
        "build": "uglifyjs decimal.js --source-map doc/decimal.js.map -c -m -o decimal.min.js --preamble \"/* decimal.js v7.1.2 https://github.com/MikeMcl/decimal.js/LICENCE */\"",
        "test": "node ./test/test.js"
    },
    "version": "7.1.2"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module decimal.js](#apidoc.module.decimal.js)
1.  boolean <span class="apidocSignatureSpan">decimal.js.</span>crypto
1.  [function <span class="apidocSignatureSpan">decimal.js.</span>Decimal (v)](#apidoc.element.decimal.js.Decimal)
1.  [function <span class="apidocSignatureSpan">decimal.js.</span>abs (x)](#apidoc.element.decimal.js.abs)
1.  [function <span class="apidocSignatureSpan">decimal.js.</span>acos (x)](#apidoc.element.decimal.js.acos)
1.  [function <span class="apidocSignatureSpan">decimal.js.</span>acosh (x)](#apidoc.element.decimal.js.acosh)
1.  [function <span class="apidocSignatureSpan">decimal.js.</span>add (x, y)](#apidoc.element.decimal.js.add)
1.  [function <span class="apidocSignatureSpan">decimal.js.</span>asin (x)](#apidoc.element.decimal.js.asin)
1.  [function <span class="apidocSignatureSpan">decimal.js.</span>asinh (x)](#apidoc.element.decimal.js.asinh)
1.  [function <span class="apidocSignatureSpan">decimal.js.</span>atan (x)](#apidoc.element.decimal.js.atan)
1.  [function <span class="apidocSignatureSpan">decimal.js.</span>atan2 (y, x)](#apidoc.element.decimal.js.atan2)
1.  [function <span class="apidocSignatureSpan">decimal.js.</span>atanh (x)](#apidoc.element.decimal.js.atanh)
1.  [function <span class="apidocSignatureSpan">decimal.js.</span>cbrt (x)](#apidoc.element.decimal.js.cbrt)
1.  [function <span class="apidocSignatureSpan">decimal.js.</span>ceil (x)](#apidoc.element.decimal.js.ceil)
1.  [function <span class="apidocSignatureSpan">decimal.js.</span>clone (obj)](#apidoc.element.decimal.js.clone)
1.  [function <span class="apidocSignatureSpan">decimal.js.</span>config (obj)](#apidoc.element.decimal.js.config)
1.  [function <span class="apidocSignatureSpan">decimal.js.</span>cos (x)](#apidoc.element.decimal.js.cos)
1.  [function <span class="apidocSignatureSpan">decimal.js.</span>cosh (x)](#apidoc.element.decimal.js.cosh)
1.  [function <span class="apidocSignatureSpan">decimal.js.</span>default (v)](#apidoc.element.decimal.js.default)
1.  [function <span class="apidocSignatureSpan">decimal.js.</span>div (x, y)](#apidoc.element.decimal.js.div)
1.  [function <span class="apidocSignatureSpan">decimal.js.</span>exp (x)](#apidoc.element.decimal.js.exp)
1.  [function <span class="apidocSignatureSpan">decimal.js.</span>floor (x)](#apidoc.element.decimal.js.floor)
1.  [function <span class="apidocSignatureSpan">decimal.js.</span>hypot ()](#apidoc.element.decimal.js.hypot)
1.  [function <span class="apidocSignatureSpan">decimal.js.</span>ln (x)](#apidoc.element.decimal.js.ln)
1.  [function <span class="apidocSignatureSpan">decimal.js.</span>log (x, y)](#apidoc.element.decimal.js.log)
1.  [function <span class="apidocSignatureSpan">decimal.js.</span>log10 (x)](#apidoc.element.decimal.js.log10)
1.  [function <span class="apidocSignatureSpan">decimal.js.</span>log2 (x)](#apidoc.element.decimal.js.log2)
1.  [function <span class="apidocSignatureSpan">decimal.js.</span>max ()](#apidoc.element.decimal.js.max)
1.  [function <span class="apidocSignatureSpan">decimal.js.</span>min ()](#apidoc.element.decimal.js.min)
1.  [function <span class="apidocSignatureSpan">decimal.js.</span>mod (x, y)](#apidoc.element.decimal.js.mod)
1.  [function <span class="apidocSignatureSpan">decimal.js.</span>mul (x, y)](#apidoc.element.decimal.js.mul)
1.  [function <span class="apidocSignatureSpan">decimal.js.</span>pow (x, y)](#apidoc.element.decimal.js.pow)
1.  [function <span class="apidocSignatureSpan">decimal.js.</span>random (sd)](#apidoc.element.decimal.js.random)
1.  [function <span class="apidocSignatureSpan">decimal.js.</span>round (x)](#apidoc.element.decimal.js.round)
1.  [function <span class="apidocSignatureSpan">decimal.js.</span>set (obj)](#apidoc.element.decimal.js.set)
1.  [function <span class="apidocSignatureSpan">decimal.js.</span>sign (x)](#apidoc.element.decimal.js.sign)
1.  [function <span class="apidocSignatureSpan">decimal.js.</span>sin (x)](#apidoc.element.decimal.js.sin)
1.  [function <span class="apidocSignatureSpan">decimal.js.</span>sinh (x)](#apidoc.element.decimal.js.sinh)
1.  [function <span class="apidocSignatureSpan">decimal.js.</span>sqrt (x)](#apidoc.element.decimal.js.sqrt)
1.  [function <span class="apidocSignatureSpan">decimal.js.</span>sub (x, y)](#apidoc.element.decimal.js.sub)
1.  [function <span class="apidocSignatureSpan">decimal.js.</span>tan (x)](#apidoc.element.decimal.js.tan)
1.  [function <span class="apidocSignatureSpan">decimal.js.</span>tanh (x)](#apidoc.element.decimal.js.tanh)
1.  [function <span class="apidocSignatureSpan">decimal.js.</span>trunc (x)](#apidoc.element.decimal.js.trunc)
1.  number <span class="apidocSignatureSpan">decimal.js.</span>EUCLID
1.  number <span class="apidocSignatureSpan">decimal.js.</span>ROUND_CEIL
1.  number <span class="apidocSignatureSpan">decimal.js.</span>ROUND_DOWN
1.  number <span class="apidocSignatureSpan">decimal.js.</span>ROUND_FLOOR
1.  number <span class="apidocSignatureSpan">decimal.js.</span>ROUND_HALF_CEIL
1.  number <span class="apidocSignatureSpan">decimal.js.</span>ROUND_HALF_DOWN
1.  number <span class="apidocSignatureSpan">decimal.js.</span>ROUND_HALF_EVEN
1.  number <span class="apidocSignatureSpan">decimal.js.</span>ROUND_HALF_FLOOR
1.  number <span class="apidocSignatureSpan">decimal.js.</span>ROUND_HALF_UP
1.  number <span class="apidocSignatureSpan">decimal.js.</span>ROUND_UP
1.  number <span class="apidocSignatureSpan">decimal.js.</span>maxE
1.  number <span class="apidocSignatureSpan">decimal.js.</span>minE
1.  number <span class="apidocSignatureSpan">decimal.js.</span>modulo
1.  number <span class="apidocSignatureSpan">decimal.js.</span>precision
1.  number <span class="apidocSignatureSpan">decimal.js.</span>rounding
1.  number <span class="apidocSignatureSpan">decimal.js.</span>toExpNeg
1.  number <span class="apidocSignatureSpan">decimal.js.</span>toExpPos



# <a name="apidoc.module.decimal.js"></a>[module decimal.js](#apidoc.module.decimal.js)

#### <a name="apidoc.element.decimal.js.Decimal"></a>[function <span class="apidocSignatureSpan">decimal.js.</span>Decimal (v)](#apidoc.element.decimal.js.Decimal)
- description and source-code
```javascript
function Decimal(v) {
  var e, i, t,
    x = this;

  // Decimal called without new.
  if (!(x instanceof Decimal)) return new Decimal(v);

  // Retain a reference to this Decimal constructor, and shadow Decimal.prototype.constructor
  // which points to Object.
  x.constructor = Decimal;

  // Duplicate.
  if (v instanceof Decimal) {
    x.s = v.s;
    x.e = v.e;
    x.d = (v = v.d) ? v.slice() : v;
    return;
  }

  t = typeof v;

  if (t === 'number') {
    if (v === 0) {
      x.s = 1 / v < 0 ? -1 : 1;
      x.e = 0;
      x.d = [0];
      return;
    }

    if (v < 0) {
      v = -v;
      x.s = -1;
    } else {
      x.s = 1;
    }

    // Fast path for small integers.
    if (v === ~~v && v < 1e7) {
      for (e = 0, i = v; i >= 10; i /= 10) e++;
      x.e = e;
      x.d = [v];
      return;

    // Infinity, NaN.
    } else if (v * 0 !== 0) {
      if (!v) x.s = NaN;
      x.e = NaN;
      x.d = null;
      return;
    }

    return parseDecimal(x, v.toString());

  } else if (t !== 'string') {
    throw Error(invalidArgument + v);
  }

  // Minus sign?
  if (v.charCodeAt(0) === 45) {
    v = v.slice(1);
    x.s = -1;
  } else {
    x.s = 1;
  }

  return isDecimal.test(v) ? parseDecimal(x, v) : parseOther(x, v);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.decimal.js.abs"></a>[function <span class="apidocSignatureSpan">decimal.js.</span>abs (x)](#apidoc.element.decimal.js.abs)
- description and source-code
```javascript
function abs(x) {
  return new this(x).abs();
}
```
- example usage
```shell
...
    external = false;

    // Initial estimate.
    s = x.s * Math.pow(x.s * x, 1 / 3);

     // Math.cbrt underflow/overflow?
     // Pass x to Math.pow as integer, then adjust the exponent of the result.
    if (!s || Math.abs(s) == 1 / 0) {
n = digitsToString(x.d);
e = x.e;

// Adjust n exponent so it is a multiple of 3 away from x exponent.
if (s = (e - n.length + 1) % 3) n += (s == 1 || s == -2 ? '0' : '00');
s = Math.pow(n, 1 / 3);
...
```

#### <a name="apidoc.element.decimal.js.acos"></a>[function <span class="apidocSignatureSpan">decimal.js.</span>acos (x)](#apidoc.element.decimal.js.acos)
- description and source-code
```javascript
function acos(x) {
  return new this(x).acos();
}
```
- example usage
```shell
...
/*
 * Return a new Decimal whose value is the arccosine in radians of 'x'.
 *
 * x {number|string|Decimal}
 *
 */
function acos(x) {
  return new this(x).acos();
}


/*
 * Return a new Decimal whose value is the inverse of the hyperbolic cosine of 'x', rounded to
 * 'precision' significant digits using rounding mode 'rounding'.
 *
...
```

#### <a name="apidoc.element.decimal.js.acosh"></a>[function <span class="apidocSignatureSpan">decimal.js.</span>acosh (x)](#apidoc.element.decimal.js.acosh)
- description and source-code
```javascript
function acosh(x) {
  return new this(x).acosh();
}
```
- example usage
```shell
...
 * Return a new Decimal whose value is the inverse of the hyperbolic cosine of 'x', rounded to
 * 'precision' significant digits using rounding mode 'rounding'.
 *
 * x {number|string|Decimal} A value in radians.
 *
 */
function acosh(x) {
  return new this(x).acosh();
}


/*
 * Return a new Decimal whose value is the sum of 'x' and 'y', rounded to 'precision' significant
 * digits using rounding mode 'rounding'.
 *
...
```

#### <a name="apidoc.element.decimal.js.add"></a>[function <span class="apidocSignatureSpan">decimal.js.</span>add (x, y)](#apidoc.element.decimal.js.add)
- description and source-code
```javascript
function add(x, y) {
  return new this(x).plus(y);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.decimal.js.asin"></a>[function <span class="apidocSignatureSpan">decimal.js.</span>asin (x)](#apidoc.element.decimal.js.asin)
- description and source-code
```javascript
function asin(x) {
  return new this(x).asin();
}
```
- example usage
```shell
...
  if (x.isZero()) return getPi(Ctor, pr + 4, rm).times(0.5);

  // TODO? Special case acos(0.5) = pi/3 and acos(-0.5) = 2*pi/3

  Ctor.precision = pr + 6;
  Ctor.rounding = 1;

  x = x.asin();
  halfPi = getPi(Ctor, pr + 4, rm).times(0.5);

  Ctor.precision = pr;
  Ctor.rounding = rm;

  return halfPi.minus(x);
};
...
```

#### <a name="apidoc.element.decimal.js.asinh"></a>[function <span class="apidocSignatureSpan">decimal.js.</span>asinh (x)](#apidoc.element.decimal.js.asinh)
- description and source-code
```javascript
function asinh(x) {
  return new this(x).asinh();
}
```
- example usage
```shell
...
 * Return a new Decimal whose value is the inverse of the hyperbolic sine of 'x', rounded to
 * 'precision' significant digits using rounding mode 'rounding'.
 *
 * x {number|string|Decimal} A value in radians.
 *
 */
function asinh(x) {
  return new this(x).asinh();
}


/*
 * Return a new Decimal whose value is the arctangent in radians of 'x', rounded to 'precision'
 * significant digits using rounding mode 'rounding'.
 *
...
```

#### <a name="apidoc.element.decimal.js.atan"></a>[function <span class="apidocSignatureSpan">decimal.js.</span>atan (x)](#apidoc.element.decimal.js.atan)
- description and source-code
```javascript
function atan(x) {
  return new this(x).atan();
}
```
- example usage
```shell
...
  }

  // TODO? Special case asin(1/2) = pi/6 and asin(-1/2) = -pi/6

  Ctor.precision = pr + 6;
  Ctor.rounding = 1;

  x = x.div(new Ctor(1).minus(x.times(x)).sqrt().plus(1)).atan();

  Ctor.precision = pr;
  Ctor.rounding = rm;

  return x.times(2);
};
...
```

#### <a name="apidoc.element.decimal.js.atan2"></a>[function <span class="apidocSignatureSpan">decimal.js.</span>atan2 (y, x)](#apidoc.element.decimal.js.atan2)
- description and source-code
```javascript
function atan2(y, x) {
  y = new this(y);
  x = new this(x);
  var r,
    pr = this.precision,
    rm = this.rounding,
    wpr = pr + 4;

  // Either NaN
  if (!y.s || !x.s) {
    r = new this(NaN);

  // Both ±Infinity
  } else if (!y.d && !x.d) {
    r = getPi(this, wpr, 1).times(x.s > 0 ? 0.25 : 0.75);
    r.s = y.s;

  // x is ±Infinity or y is ±0
  } else if (!x.d || y.isZero()) {
    r = x.s < 0 ? getPi(this, pr, rm) : new this(0);
    r.s = y.s;

  // y is ±Infinity or x is ±0
  } else if (!y.d || x.isZero()) {
    r = getPi(this, wpr, 1).times(0.5);
    r.s = y.s;

  // Both non-zero and finite
  } else if (x.s < 0) {
    this.precision = wpr;
    this.rounding = 1;
    r = this.atan(divide(y, x, wpr, 1));
    x = getPi(this, wpr, 1);
    this.precision = pr;
    this.rounding = rm;
    r = y.s < 0 ? r.minus(x) : r.plus(x);
  } else {
    r = this.atan(divide(y, x, wpr, 1));
  }

  return r;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.decimal.js.atanh"></a>[function <span class="apidocSignatureSpan">decimal.js.</span>atanh (x)](#apidoc.element.decimal.js.atanh)
- description and source-code
```javascript
function atanh(x) {
  return new this(x).atanh();
}
```
- example usage
```shell
...
 * Return a new Decimal whose value is the inverse of the hyperbolic tangent of 'x', rounded to
 * 'precision' significant digits using rounding mode 'rounding'.
 *
 * x {number|string|Decimal} A value in radians.
 *
 */
function atanh(x) {
  return new this(x).atanh();
}


/*
 * Return a new Decimal whose value is the arctangent in radians of 'y/x' in the range -pi to pi
 * (inclusive), rounded to 'precision' significant digits using rounding mode 'rounding'.
 *
...
```

#### <a name="apidoc.element.decimal.js.cbrt"></a>[function <span class="apidocSignatureSpan">decimal.js.</span>cbrt (x)](#apidoc.element.decimal.js.cbrt)
- description and source-code
```javascript
function cbrt(x) {
  return new this(x).cbrt();
}
```
- example usage
```shell
...
 *  cbrt(-0) = -0
 *  cbrt(1)  =  1
 *  cbrt(-1) = -1
 *  cbrt(N)  =  N
 *  cbrt(-I) = -I
 *  cbrt(I)  =  I
 *
 * Math.cbrt(x) = (x < 0 ? -Math.pow(-x, 1/3) : Math.pow(x, 1/3))
 *
 */
P.cubeRoot = P.cbrt = function () {
  var e, m, n, r, rep, s, sd, t, t3, t3plusx,
    x = this,
    Ctor = x.constructor;
...
```

#### <a name="apidoc.element.decimal.js.ceil"></a>[function <span class="apidocSignatureSpan">decimal.js.</span>ceil (x)](#apidoc.element.decimal.js.ceil)
- description and source-code
```javascript
function ceil(x) {
  return finalise(x = new this(x), x.e + 1, 2);
}
```
- example usage
```shell
...
x                             // '0.3'
'''

The methods that return a Decimal can be chained.

'''js
x.dividedBy(y).plus(z).times(9).floor()
x.times('1.23456780123456789e+9').plus(9876.5432321).dividedBy('4444562598.111772').ceil()
'''

Many method names have a shorter alias.

'''js
x.squareRoot().dividedBy(y).toPower(3).equals(x.sqrt().div(y).pow(3))         // true
x.cmp(y.mod(z).neg()) == 1 && x.comparedTo(y.modulo(z).negated()) == 1        // true
...
```

#### <a name="apidoc.element.decimal.js.clone"></a>[function <span class="apidocSignatureSpan">decimal.js.</span>clone (obj)](#apidoc.element.decimal.js.clone)
- description and source-code
```javascript
function clone(obj) {
  var i, p, ps;

  /*
   * The Decimal constructor and exported function.
   * Return a new Decimal instance.
   *
   * v {number|string|Decimal} A numeric value.
   *
   */
  function Decimal(v) {
    var e, i, t,
      x = this;

    // Decimal called without new.
    if (!(x instanceof Decimal)) return new Decimal(v);

    // Retain a reference to this Decimal constructor, and shadow Decimal.prototype.constructor
    // which points to Object.
    x.constructor = Decimal;

    // Duplicate.
    if (v instanceof Decimal) {
      x.s = v.s;
      x.e = v.e;
      x.d = (v = v.d) ? v.slice() : v;
      return;
    }

    t = typeof v;

    if (t === 'number') {
      if (v === 0) {
        x.s = 1 / v < 0 ? -1 : 1;
        x.e = 0;
        x.d = [0];
        return;
      }

      if (v < 0) {
        v = -v;
        x.s = -1;
      } else {
        x.s = 1;
      }

      // Fast path for small integers.
      if (v === ~~v && v < 1e7) {
        for (e = 0, i = v; i >= 10; i /= 10) e++;
        x.e = e;
        x.d = [v];
        return;

      // Infinity, NaN.
      } else if (v * 0 !== 0) {
        if (!v) x.s = NaN;
        x.e = NaN;
        x.d = null;
        return;
      }

      return parseDecimal(x, v.toString());

    } else if (t !== 'string') {
      throw Error(invalidArgument + v);
    }

    // Minus sign?
    if (v.charCodeAt(0) === 45) {
      v = v.slice(1);
      x.s = -1;
    } else {
      x.s = 1;
    }

    return isDecimal.test(v) ? parseDecimal(x, v) : parseOther(x, v);
  }

  Decimal.prototype = P;

  Decimal.ROUND_UP = 0;
  Decimal.ROUND_DOWN = 1;
  Decimal.ROUND_CEIL = 2;
  Decimal.ROUND_FLOOR = 3;
  Decimal.ROUND_HALF_UP = 4;
  Decimal.ROUND_HALF_DOWN = 5;
  Decimal.ROUND_HALF_EVEN = 6;
  Decimal.ROUND_HALF_CEIL = 7;
  Decimal.ROUND_HALF_FLOOR = 8;
  Decimal.EUCLID = 9;

  Decimal.config = Decimal.set = config;
  Decimal.clone = clone;

  Decimal.abs = abs;
  Decimal.acos = acos;
  Decimal.acosh = acosh;        // ES6
  Decimal.add = add;
  Decimal.asin = asin;
  Decimal.asinh = asinh;        // ES6
  Decimal.atan = atan;
  Decimal.atanh = atanh;        // ES6
  Decimal.atan2 = atan2;
  Decimal.cbrt = cbrt;          // ES6
  Decimal.ceil = ceil;
  Decimal.cos = cos;
  Decimal.cosh = cosh;          // ES6
  Decimal.div = div;
  Decimal.exp = exp;
  Decimal.floor = floor;
  Decimal.hypot = hypot;        // ES6
  Decimal.ln = ln;
  Decimal.log = log;
  Decimal.log10 = log10;        // ES6
  Decimal.log2 = log2;          // ES6
  Decimal.max = max;
  Decimal.min = min;
  Decimal.mod = mod;
  Decimal.mul = mul;
  Decimal.pow = pow;
  Decimal.random = random;
  Decimal.round = round;
  Decimal.sign = sign;          // ES6
  Decimal.sin = sin;
  Decimal.sinh = sinh;          // ES6
  Decimal.sqrt = sqrt;
  Decimal.sub = sub;
  Decimal.tan = tan;
  Decimal.tanh = tanh;          // ES6
  Decimal.trunc = trunc;        // ES6

  if (obj === void 0) obj = {};
  if (obj) {
    ps = ['precision', 'rounding', 'toExpNeg', 'toExpPos', 'maxE', 'minE', 'modulo', 'crypto'];
    for (i = 0; i < ps.length;) if (!obj.hasOwnProperty(p = ps[i++])) obj[p] = this[p];
  }

  Decimal.config(obj);

  return Decimal;
}
```
- example usage
```shell
...
applies to all Decimal numbers created from it.

'''js
// Set the precision and rounding of the default Decimal constructor
Decimal.set({ precision: 5, rounding: 4 })

// Create another Decimal constructor, optionally passing in a configuration object
Decimal10 = Decimal.clone({ precision: 10, rounding: 1 })

x = new Decimal(5)
y = new Decimal10(5)

x.div(3)                           // '1.6667'
y.div(3)                           // '1.666666666'
'''
...
```

#### <a name="apidoc.element.decimal.js.config"></a>[function <span class="apidocSignatureSpan">decimal.js.</span>config (obj)](#apidoc.element.decimal.js.config)
- description and source-code
```javascript
function config(obj) {
  if (!obj || typeof obj !== 'object') throw Error(decimalError + 'Object expected');
  var i, p, v,
    ps = [
      'precision', 1, MAX_DIGITS,
      'rounding', 0, 8,
      'toExpNeg', -EXP_LIMIT, 0,
      'toExpPos', 0, EXP_LIMIT,
      'maxE', 0, EXP_LIMIT,
      'minE', -EXP_LIMIT, 0,
      'modulo', 0, 9
    ];

  for (i = 0; i < ps.length; i += 3) {
    if ((v = obj[p = ps[i]]) !== void 0) {
      if (mathfloor(v) === v && v >= ps[i + 1] && v <= ps[i + 2]) this[p] = v;
      else throw Error(invalidArgument + p + ': ' + v);
    }
  }

  if ((v = obj[p = 'crypto']) !== void 0) {
    if (v === true || v === false || v === 0 || v === 1) {
      if (v) {
        if (typeof crypto != 'undefined' && crypto &&
          (crypto.getRandomValues || crypto.randomBytes)) {
          this[p] = true;
        } else {
          throw Error(cryptoUnavailable);
        }
      } else {
        this[p] = false;
      }
    } else {
      throw Error(invalidArgument + p + ': ' + v);
    }
  }

  return this;
}
```
- example usage
```shell
...
    // The initial configuration properties of the Decimal constructor.
    Decimal = {

// These values must be integers within the stated ranges (inclusive).
// Most of these values can be changed at run-time using the 'Decimal.config' method.

// The maximum number of significant digits of the result of a calculation or base conversion.
// E.g. 'Decimal.config({ precision: 20 });'
precision: 20,                         // 1 to MAX_DIGITS

// The rounding mode used when rounding to 'precision'.
//
// ROUND_UP         0 Away from zero.
// ROUND_DOWN       1 Towards zero.
// ROUND_CEIL       2 Towards +Infinity.
...
```

#### <a name="apidoc.element.decimal.js.cos"></a>[function <span class="apidocSignatureSpan">decimal.js.</span>cos (x)](#apidoc.element.decimal.js.cos)
- description and source-code
```javascript
function cos(x) {
  return new this(x).cos();
}
```
- example usage
```shell
...
 * Return a new Decimal whose value is the cosine of 'x', rounded to 'precision' significant
 * digits using rounding mode 'rounding'.
 *
 * x {number|string|Decimal} A value in radians.
 *
 */
function cos(x) {
  return new this(x).cos();
}


/*
 * Return a new Decimal whose value is the hyperbolic cosine of 'x', rounded to precision
 * significant digits using rounding mode 'rounding'.
 *
...
```

#### <a name="apidoc.element.decimal.js.cosh"></a>[function <span class="apidocSignatureSpan">decimal.js.</span>cosh (x)](#apidoc.element.decimal.js.cosh)
- description and source-code
```javascript
function cosh(x) {
  return new this(x).cosh();
}
```
- example usage
```shell
...
  if (x.isZero()) return new Ctor(x);

  pr = Ctor.precision;
  rm = Ctor.rounding;
  Ctor.precision = pr + 7;
  Ctor.rounding = 1;

  return divide(x.sinh(), x.cosh(), Ctor.precision = pr, Ctor.rounding = rm);
};


/*
 * Return a new Decimal whose value is the arccosine (inverse cosine) in radians of the value of
 * this Decimal.
 *
...
```

#### <a name="apidoc.element.decimal.js.default"></a>[function <span class="apidocSignatureSpan">decimal.js.</span>default (v)](#apidoc.element.decimal.js.default)
- description and source-code
```javascript
function Decimal(v) {
  var e, i, t,
    x = this;

  // Decimal called without new.
  if (!(x instanceof Decimal)) return new Decimal(v);

  // Retain a reference to this Decimal constructor, and shadow Decimal.prototype.constructor
  // which points to Object.
  x.constructor = Decimal;

  // Duplicate.
  if (v instanceof Decimal) {
    x.s = v.s;
    x.e = v.e;
    x.d = (v = v.d) ? v.slice() : v;
    return;
  }

  t = typeof v;

  if (t === 'number') {
    if (v === 0) {
      x.s = 1 / v < 0 ? -1 : 1;
      x.e = 0;
      x.d = [0];
      return;
    }

    if (v < 0) {
      v = -v;
      x.s = -1;
    } else {
      x.s = 1;
    }

    // Fast path for small integers.
    if (v === ~~v && v < 1e7) {
      for (e = 0, i = v; i >= 10; i /= 10) e++;
      x.e = e;
      x.d = [v];
      return;

    // Infinity, NaN.
    } else if (v * 0 !== 0) {
      if (!v) x.s = NaN;
      x.e = NaN;
      x.d = null;
      return;
    }

    return parseDecimal(x, v.toString());

  } else if (t !== 'string') {
    throw Error(invalidArgument + v);
  }

  // Minus sign?
  if (v.charCodeAt(0) === 45) {
    v = v.slice(1);
    x.s = -1;
  } else {
    x.s = 1;
  }

  return isDecimal.test(v) ? parseDecimal(x, v) : parseOther(x, v);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.decimal.js.div"></a>[function <span class="apidocSignatureSpan">decimal.js.</span>div (x, y)](#apidoc.element.decimal.js.div)
- description and source-code
```javascript
function div(x, y) {
  return new this(x).div(y);
}
```
- example usage
```shell
...
x.dividedBy(y).plus(z).times(9).floor()
x.times('1.23456780123456789e+9').plus(9876.5432321).dividedBy('4444562598.111772').ceil()
'''

Many method names have a shorter alias.

'''js
x.squareRoot().dividedBy(y).toPower(3).equals(x.sqrt().div(y).pow(3))         // true
x.cmp(y.mod(z).neg()) == 1 && x.comparedTo(y.modulo(z).negated()) == 1        // true
'''

Like JavaScript's Number type, there are 'toExponential', 'toFixed' and 'toPrecision' methods,

'''js
x = new Decimal(255.5)
...
```

#### <a name="apidoc.element.decimal.js.exp"></a>[function <span class="apidocSignatureSpan">decimal.js.</span>exp (x)](#apidoc.element.decimal.js.exp)
- description and source-code
```javascript
function exp(x) {
  return new this(x).exp();
}
```
- example usage
```shell
...
* Previously, the argument was initially reduced by
* exp(x) = exp(r) * 10^k  where r = x - k * ln10, k = floor(x / ln10)
* to first put r in the range [0, ln10], before dividing by 32 until |x| < 0.1, but this was
* found to be slower than just dividing repeatedly by 32 as above.
*
* Max integer argument: exp('20723265836946413') = 6.3e+9000000000000000
* Min integer argument: exp('-20723265836946411') = 1.2e-9000000000000000
* (Math object integer min/max: Math.exp(709) = 8.2e+307, Math.exp(-745) = 5e-324)
*
*  exp(Infinity)  = Infinity
*  exp(-Infinity) = 0
*  exp(NaN)       = NaN
*  exp(±0)        = 1
*
*  exp(x) is non-terminating for any finite, non-zero x.
...
```

#### <a name="apidoc.element.decimal.js.floor"></a>[function <span class="apidocSignatureSpan">decimal.js.</span>floor (x)](#apidoc.element.decimal.js.floor)
- description and source-code
```javascript
function floor(x) {
  return finalise(x = new this(x), x.e + 1, 3);
}
```
- example usage
```shell
...
x.minus(0.1)                  // '0.2'
x                             // '0.3'
'''

The methods that return a Decimal can be chained.

'''js
x.dividedBy(y).plus(z).times(9).floor()
x.times('1.23456780123456789e+9').plus(9876.5432321).dividedBy('4444562598.111772').ceil()
'''

Many method names have a shorter alias.

'''js
x.squareRoot().dividedBy(y).toPower(3).equals(x.sqrt().div(y).pow(3))         // true
...
```

#### <a name="apidoc.element.decimal.js.hypot"></a>[function <span class="apidocSignatureSpan">decimal.js.</span>hypot ()](#apidoc.element.decimal.js.hypot)
- description and source-code
```javascript
function hypot() {
  var i, n,
    t = new this(0);

  external = false;

  for (i = 0; i < arguments.length;) {
    n = new this(arguments[i++]);
    if (!n.d) {
      if (n.s) {
        external = true;
        return new this(1 / 0);
      }
      t = n;
    } else if (t.d) {
      t = t.plus(n.times(n));
    }
  }

  external = true;

  return t.sqrt();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.decimal.js.ln"></a>[function <span class="apidocSignatureSpan">decimal.js.</span>ln (x)](#apidoc.element.decimal.js.ln)
- description and source-code
```javascript
function ln(x) {
  return new this(x).ln();
}
```
- example usage
```shell
...

  x = x.times(x).minus(1).sqrt().plus(x);

  external = true;
  Ctor.precision = pr;
  Ctor.rounding = rm;

  return x.ln();
};


/*
 * Return a new Decimal whose value is the inverse of the hyperbolic sine in radians of the value
 * of this Decimal.
 *
...
```

#### <a name="apidoc.element.decimal.js.log"></a>[function <span class="apidocSignatureSpan">decimal.js.</span>log (x, y)](#apidoc.element.decimal.js.log)
- description and source-code
```javascript
function log(x, y) {
  return new this(x).log(y);
}
```
- example usage
```shell
...

// Estimate result exponent.
// x^y = 10^e,  where e = y * log10(x)
// log10(x) = log10(x_significand) + x_exponent
// log10(x_significand) = ln(x_significand) / ln(10)
k = mathpow(+x, yn);
e = k == 0 || !isFinite(k)
  ? mathfloor(yn * (Math.log('0.' + digitsToString(x.d)) / Math.LN10 + x.e + 1))
  : new Ctor(k + '').e;

// Estimate may be incorrect e.g. x: 0.999999999999999999, y: 2.29, e: 0, r.e: -1.

// Overflow/underflow?
if (e > Ctor.maxE + 1 || e < Ctor.minE - 1) return new Ctor(e > 0 ? sign / 0 : 0);
...
```

#### <a name="apidoc.element.decimal.js.log10"></a>[function <span class="apidocSignatureSpan">decimal.js.</span>log10 (x)](#apidoc.element.decimal.js.log10)
- description and source-code
```javascript
function log10(x) {
  return new this(x).log(10);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.decimal.js.log2"></a>[function <span class="apidocSignatureSpan">decimal.js.</span>log2 (x)](#apidoc.element.decimal.js.log2)
- description and source-code
```javascript
function log2(x) {
  return new this(x).log(2);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.decimal.js.max"></a>[function <span class="apidocSignatureSpan">decimal.js.</span>max ()](#apidoc.element.decimal.js.max)
- description and source-code
```javascript
function max() {
  return maxOrMin(this, arguments, 'lt');
}
```
- example usage
```shell
...
if (!x.d) return new Ctor(NaN);

// cos(0) = cos(-0) = 1
if (!x.d[0]) return new Ctor(1);

pr = Ctor.precision;
rm = Ctor.rounding;
Ctor.precision = pr + Math.max(x.e, x.sd()) + LOG_BASE;
Ctor.rounding = 1;

x = cosine(Ctor, toLessThanHalfPi(Ctor, x));

Ctor.precision = pr;
Ctor.rounding = rm;
...
```

#### <a name="apidoc.element.decimal.js.min"></a>[function <span class="apidocSignatureSpan">decimal.js.</span>min ()](#apidoc.element.decimal.js.min)
- description and source-code
```javascript
function min() {
  return maxOrMin(this, arguments, 'gt');
}
```
- example usage
```shell
...

// TODO? if (x >= 1 && pr <= PI_PRECISION) atan(x) = halfPi * x.s - atan(1 / x);

// Argument reduction
// Ensure |x| < 0.42
// atan(x) = 2 * atan(x / (1 + sqrt(1 + x^2)))

k = Math.min(28, wpr / LOG_BASE + 2 | 0);

for (i = k; i; --i) x = x.div(x.times(x).plus(1).sqrt().plus(1));

external = false;

j = Math.ceil(wpr / LOG_BASE);
n = 1;
...
```

#### <a name="apidoc.element.decimal.js.mod"></a>[function <span class="apidocSignatureSpan">decimal.js.</span>mod (x, y)](#apidoc.element.decimal.js.mod)
- description and source-code
```javascript
function mod(x, y) {
  return new this(x).mod(y);
}
```
- example usage
```shell
...
x.times('1.23456780123456789e+9').plus(9876.5432321).dividedBy('4444562598.111772').ceil()
'''

Many method names have a shorter alias.

'''js
x.squareRoot().dividedBy(y).toPower(3).equals(x.sqrt().div(y).pow(3))         // true
x.cmp(y.mod(z).neg()) == 1 && x.comparedTo(y.modulo(z).negated()) == 1        // true
'''

Like JavaScript's Number type, there are 'toExponential', 'toFixed' and 'toPrecision' methods,

'''js
x = new Decimal(255.5)
x.toExponential(5)              // '2.55500e+2'
...
```

#### <a name="apidoc.element.decimal.js.mul"></a>[function <span class="apidocSignatureSpan">decimal.js.</span>mul (x, y)](#apidoc.element.decimal.js.mul)
- description and source-code
```javascript
function mul(x, y) {
  return new this(x).mul(y);
}
```
- example usage
```shell
...
 * digits using rounding mode 'rounding'.
 *
 * x {number|string|Decimal}
 * y {number|string|Decimal}
 *
 */
function mul(x, y) {
  return new this(x).mul(y);
}


/*
 * Return a new Decimal whose value is 'x' raised to the power 'y', rounded to precision
 * significant digits using rounding mode 'rounding'.
 *
...
```

#### <a name="apidoc.element.decimal.js.pow"></a>[function <span class="apidocSignatureSpan">decimal.js.</span>pow (x, y)](#apidoc.element.decimal.js.pow)
- description and source-code
```javascript
function pow(x, y) {
  return new this(x).pow(y);
}
```
- example usage
```shell
...
x.dividedBy(y).plus(z).times(9).floor()
x.times('1.23456780123456789e+9').plus(9876.5432321).dividedBy('4444562598.111772').ceil()
'''

Many method names have a shorter alias.

'''js
x.squareRoot().dividedBy(y).toPower(3).equals(x.sqrt().div(y).pow(3))         // true
x.cmp(y.mod(z).neg()) == 1 && x.comparedTo(y.modulo(z).negated()) == 1        // true
'''

Like JavaScript's Number type, there are 'toExponential', 'toFixed' and 'toPrecision' methods,

'''js
x = new Decimal(255.5)
...
```

#### <a name="apidoc.element.decimal.js.random"></a>[function <span class="apidocSignatureSpan">decimal.js.</span>random (sd)](#apidoc.element.decimal.js.random)
- description and source-code
```javascript
function random(sd) {
  var d, e, k, n,
    i = 0,
    r = new this(1),
    rd = [];

  if (sd === void 0) sd = this.precision;
  else checkInt32(sd, 1, MAX_DIGITS);

  k = Math.ceil(sd / LOG_BASE);

  if (!this.crypto) {
    for (; i < k;) rd[i++] = Math.random() * 1e7 | 0;

  // Browsers supporting crypto.getRandomValues.
  } else if (crypto.getRandomValues) {
    d = crypto.getRandomValues(new Uint32Array(k));

    for (; i < k;) {
      n = d[i];

      // 0 <= n < 4294967296
      // Probability n >= 4.29e9, is 4967296 / 4294967296 = 0.00116 (1 in 865).
      if (n >= 4.29e9) {
        d[i] = crypto.getRandomValues(new Uint32Array(1))[0];
      } else {

        // 0 <= n <= 4289999999
        // 0 <= (n % 1e7) <= 9999999
        rd[i++] = n % 1e7;
      }
    }

  // Node.js supporting crypto.randomBytes.
  } else if (crypto.randomBytes) {

    // buffer
    d = crypto.randomBytes(k *= 4);

    for (; i < k;) {

      // 0 <= n < 2147483648
      n = d[i] + (d[i + 1] << 8) + (d[i + 2] << 16) + ((d[i + 3] & 0x7f) << 24);

      // Probability n >= 2.14e9, is 7483648 / 2147483648 = 0.0035 (1 in 286).
      if (n >= 2.14e9) {
        crypto.randomBytes(4).copy(d, i);
      } else {

        // 0 <= n <= 2139999999
        // 0 <= (n % 1e7) <= 9999999
        rd.push(n % 1e7);
        i += 4;
      }
    }

    i = k / 4;
  } else {
    throw Error(cryptoUnavailable);
  }

  k = rd[--i];
  sd %= LOG_BASE;

  // Convert trailing digits to zeros according to sd.
  if (k && sd) {
    n = mathpow(10, LOG_BASE - sd);
    rd[i] = (k / n | 0) * n;
  }

  // Remove trailing words which are zero.
  for (; rd[i] === 0; i--) rd.pop();

  // Zero?
  if (i < 0) {
    e = 0;
    rd = [0];
  } else {
    e = -1;

    // Remove leading words which are zero and adjust exponent accordingly.
    for (; rd[0] === 0; e -= LOG_BASE) rd.shift();

    // Count the digits of the first word of rd to determine leading zeros.
    for (k = 1, n = rd[0]; n >= 10; n /= 10) k++;

    // Adjust the exponent for leading zeros of the first word of rd.
    if (k < LOG_BASE) e -= LOG_BASE - k;
  }

  r.e = e;
  r.d = rd;

  return r;
}
```
- example usage
```shell
...

    if (sd === void 0) sd = this.precision;
    else checkInt32(sd, 1, MAX_DIGITS);

    k = Math.ceil(sd / LOG_BASE);

    if (!this.crypto) {
for (; i < k;) rd[i++] = Math.random() * 1e7 | 0;

    // Browsers supporting crypto.getRandomValues.
    } else if (crypto.getRandomValues) {
d = crypto.getRandomValues(new Uint32Array(k));

for (; i < k;) {
  n = d[i];
...
```

#### <a name="apidoc.element.decimal.js.round"></a>[function <span class="apidocSignatureSpan">decimal.js.</span>round (x)](#apidoc.element.decimal.js.round)
- description and source-code
```javascript
function round(x) {
  return finalise(x = new this(x), x.e + 1, this.rounding);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.decimal.js.set"></a>[function <span class="apidocSignatureSpan">decimal.js.</span>set (obj)](#apidoc.element.decimal.js.set)
- description and source-code
```javascript
function config(obj) {
  if (!obj || typeof obj !== 'object') throw Error(decimalError + 'Object expected');
  var i, p, v,
    ps = [
      'precision', 1, MAX_DIGITS,
      'rounding', 0, 8,
      'toExpNeg', -EXP_LIMIT, 0,
      'toExpPos', 0, EXP_LIMIT,
      'maxE', 0, EXP_LIMIT,
      'minE', -EXP_LIMIT, 0,
      'modulo', 0, 9
    ];

  for (i = 0; i < ps.length; i += 3) {
    if ((v = obj[p = ps[i]]) !== void 0) {
      if (mathfloor(v) === v && v >= ps[i + 1] && v <= ps[i + 2]) this[p] = v;
      else throw Error(invalidArgument + p + ': ' + v);
    }
  }

  if ((v = obj[p = 'crypto']) !== void 0) {
    if (v === true || v === false || v === 0 || v === 1) {
      if (v) {
        if (typeof crypto != 'undefined' && crypto &&
          (crypto.getRandomValues || crypto.randomBytes)) {
          this[p] = true;
        } else {
          throw Error(cryptoUnavailable);
        }
      } else {
        this[p] = false;
      }
    } else {
      throw Error(invalidArgument + p + ': ' + v);
    }
  }

  return this;
}
```
- example usage
```shell
...
specified by the 'precision' and 'rounding' properties of the Decimal constructor.

Multiple Decimal constructors can be created, each with their own independent configuration which
applies to all Decimal numbers created from it.

'''js
// Set the precision and rounding of the default Decimal constructor
Decimal.set({ precision: 5, rounding: 4 })

// Create another Decimal constructor, optionally passing in a configuration object
Decimal10 = Decimal.clone({ precision: 10, rounding: 1 })

x = new Decimal(5)
y = new Decimal10(5)
...
```

#### <a name="apidoc.element.decimal.js.sign"></a>[function <span class="apidocSignatureSpan">decimal.js.</span>sign (x)](#apidoc.element.decimal.js.sign)
- description and source-code
```javascript
function sign(x) {
  x = new this(x);
  return x.d ? (x.d[0] ? x.s : 0 * x.s) : x.s || NaN;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.decimal.js.sin"></a>[function <span class="apidocSignatureSpan">decimal.js.</span>sin (x)](#apidoc.element.decimal.js.sin)
- description and source-code
```javascript
function sin(x) {
  return new this(x).sin();
}
```
- example usage
```shell
...
if (x.isZero()) return new Ctor(x);

pr = Ctor.precision;
rm = Ctor.rounding;
Ctor.precision = pr + 10;
Ctor.rounding = 1;

x = x.sin();
x.s = 1;
x = divide(x, new Ctor(1).minus(x.times(x)).sqrt(), pr + 10, 0);

Ctor.precision = pr;
Ctor.rounding = rm;

return finalise(quadrant == 2 || quadrant == 4 ? x.neg() : x, pr, rm, true);
...
```

#### <a name="apidoc.element.decimal.js.sinh"></a>[function <span class="apidocSignatureSpan">decimal.js.</span>sinh (x)](#apidoc.element.decimal.js.sinh)
- description and source-code
```javascript
function sinh(x) {
  return new this(x).sinh();
}
```
- example usage
```shell
...
  if (x.isZero()) return new Ctor(x);

  pr = Ctor.precision;
  rm = Ctor.rounding;
  Ctor.precision = pr + 7;
  Ctor.rounding = 1;

  return divide(x.sinh(), x.cosh(), Ctor.precision = pr, Ctor.rounding = rm);
};


/*
 * Return a new Decimal whose value is the arccosine (inverse cosine) in radians of the value of
 * this Decimal.
 *
...
```

#### <a name="apidoc.element.decimal.js.sqrt"></a>[function <span class="apidocSignatureSpan">decimal.js.</span>sqrt (x)](#apidoc.element.decimal.js.sqrt)
- description and source-code
```javascript
function sqrt(x) {
  return new this(x).sqrt();
}
```
- example usage
```shell
...
x.dividedBy(y).plus(z).times(9).floor()
x.times('1.23456780123456789e+9').plus(9876.5432321).dividedBy('4444562598.111772').ceil()
'''

Many method names have a shorter alias.

'''js
x.squareRoot().dividedBy(y).toPower(3).equals(x.sqrt().div(y).pow(3))         // true
x.cmp(y.mod(z).neg()) == 1 && x.comparedTo(y.modulo(z).negated()) == 1        // true
'''

Like JavaScript's Number type, there are 'toExponential', 'toFixed' and 'toPrecision' methods,

'''js
x = new Decimal(255.5)
...
```

#### <a name="apidoc.element.decimal.js.sub"></a>[function <span class="apidocSignatureSpan">decimal.js.</span>sub (x, y)](#apidoc.element.decimal.js.sub)
- description and source-code
```javascript
function sub(x, y) {
  return new this(x).sub(y);
}
```
- example usage
```shell
...
 * using rounding mode 'rounding'.
 *
 * x {number|string|Decimal}
 * y {number|string|Decimal}
 *
 */
function sub(x, y) {
  return new this(x).sub(y);
}


/*
 * Return a new Decimal whose value is the tangent of 'x', rounded to 'precision' significant
 * digits using rounding mode 'rounding'.
 *
...
```

#### <a name="apidoc.element.decimal.js.tan"></a>[function <span class="apidocSignatureSpan">decimal.js.</span>tan (x)](#apidoc.element.decimal.js.tan)
- description and source-code
```javascript
function tan(x) {
  return new this(x).tan();
}
```
- example usage
```shell
...
 * Return a new Decimal whose value is the tangent of 'x', rounded to 'precision' significant
 * digits using rounding mode 'rounding'.
 *
 * x {number|string|Decimal} A value in radians.
 *
 */
function tan(x) {
  return new this(x).tan();
}


/*
 * Return a new Decimal whose value is the hyperbolic tangent of 'x', rounded to 'precision'
 * significant digits using rounding mode 'rounding'.
 *
...
```

#### <a name="apidoc.element.decimal.js.tanh"></a>[function <span class="apidocSignatureSpan">decimal.js.</span>tanh (x)](#apidoc.element.decimal.js.tanh)
- description and source-code
```javascript
function tanh(x) {
  return new this(x).tanh();
}
```
- example usage
```shell
...
 * Return a new Decimal whose value is the hyperbolic tangent of 'x', rounded to 'precision'
 * significant digits using rounding mode 'rounding'.
 *
 * x {number|string|Decimal} A value in radians.
 *
 */
function tanh(x) {
  return new this(x).tanh();
}


/*
 * Return a new Decimal whose value is 'x' truncated to an integer.
 *
 * x {number|string|Decimal}
...
```

#### <a name="apidoc.element.decimal.js.trunc"></a>[function <span class="apidocSignatureSpan">decimal.js.</span>trunc (x)](#apidoc.element.decimal.js.trunc)
- description and source-code
```javascript
function trunc(x) {
  return finalise(x = new this(x), x.e + 1, 1);
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
