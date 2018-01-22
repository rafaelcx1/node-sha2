# `sha2`

This Javascript module implements the SHA-2 (Secure Hash Algorithm 2) cryptographic hash function family designed by _the United States National Security Agency (NSA)_.
It makes use of [the `crypto` standard built-in module](https://github.com/nodejs/node/blob/master/lib/crypto.js) if the module is available (e.g. on Node.js), otherwise (e.g. on web browsers), an alternative Javascript implementation for SHA-2 that I developed is used.


## Installation ⤓

```
npm install sha2
```

or just download [the `SHA2.js`](./SHA2.js).


## API

.


## Example

.


## Warning ⚠️

Making a hash of a password with one of the algorithms of the SHA-2 family and keeping it, is **not recommended**.
For that purpose, use slow hash functions which are slow by design such as [PBKDF2](http://en.wikipedia.org/wiki/PBKDF2), [bcrypt](https://en.wikipedia.org/wiki/bcrypt) and [scrypt](http://www.tarsnap.com/scrypt.html), instead.

- [How to securely hash passwords? <sub>(_Information security Stack Exchange_)</sub>](https://security.stackexchange.com/a/31846/135187)
- [Salted Password Hashing - Doing it Right <sub>(_CrackStation_)</sub>](https://crackstation.net/hashing-security.htm)
- [How To Safely Store A Password <sub>(_Coda Hale_)</sub>](https://codahale.com/how-to-safely-store-a-password/)


## Specification reference 📖

### [Request for Comments #6234<sup>(RFC 6234)</sup> <sub>‘US Secure Hash Algorithms (SHA and SHA-based HMAC and HKDF)’</sub>](https://tools.ietf.org/html/rfc6234)

- **§1**: Overview of Contents.
- **§2**: Notation for Bit Strings and Integers.
- **§3**: Operations on Words.
- **§4**: Message Padding and Parsing.
- **§5**: Functions and Constants Used.
- **§6**: Computing the Message Digest.

written by _Donald E. Eastlake 3rd_, and _Tony Hansen_ in May 2011.

### [Federal Information Processing Standards Publication 180-4<sup>(FIPS PUB 180-4)</sup> <sub>‘Secure Hash Standard (SHS)’</sub>](http://nvlpubs.nist.gov/nistpubs/FIPS/NIST.FIPS.180-4.pdf)

- **§5.3.6**: SHA-512/t.

published by _National Institute of Standards and Technology (NIST)_ in August 2015.


## License 📜

This Javascript module has been licensed under the MIT license:

```javascript
/*
	SHA2.js
	(Javascript implementation of
	the United States of America (USA)
	Federal Information Processing Standard (FIPS)
	Secure Hash Algorithm 2 (SHA-2))
	for Node.js and web browsers

		developed
			by K. (https://github.com/wlzla000)
			on January 16-23, 2018,

		licensed under


		the MIT license

		Copyright (c) 2018 K.

		 Permission is hereby granted, free of charge, to any person
		obtaining a copy of this software and associated documentation
		files (the "Software"), to deal in the Software without
		restriction, including without limitation the rights to use,
		copy, modify, merge, publish, distribute, sublicense, and/or
		sell copies of the Software, and to permit persons to whom the
		Software is furnished to do so, subject to the following
		conditions:

		 The above copyright notice and this permission notice shall be
		included in all copies or substantial portions of the Software.

		 THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
		EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES
		OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
		NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT
		HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY,
		WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING
		FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR
		OTHER DEALINGS IN THE SOFTWARE.
*/
```

, and its dependency [`crypto` also has the MIT license](https://github.com/nodejs/node/blob/master/lib/crypto.js#L1-L21).


## Special thanks

Thank you for providing [a great piece of music for programming](https://www.youtube.com/watch?v=jJHe4i90Ua0),
[_Nick Kaelar_](https://www.youtube.com/user/varienofficial) and [_Team Salvato_](https://www.youtube.com/channel/UC41-En1dwTQ6SRtDH0oY8bw)!
