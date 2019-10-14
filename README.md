# bech32-js
Javascript validation for Bech32  [BIP173](https://github.com/bitcoin/bips/blob/master/bip-0173.mediawiki) bitcoin addresses.


## Example

``` html
<script src="bech32-js.min.js"></script>
```

``` javascript
var result = checkbech32('abcdef1qpzry9x8gf2tvdw0s3jn54khce6mua7lmqqqxw')
// => 'OK'
var result = checkbech32('wrongabcdef1qpzry9x8gf2tvdw0s3jnkhce6muawrong')
// => 'KO'

```





## Credits
- [bitcoinjs contributors](https://github.com/bitcoinjs) for the Bech32 encoding/decoding [library](https://github.com/bitcoinjs/bech32)
- [Peter Wuille](https://github.com/sipa/bech32) for the reference JavaScript implementation, and for authoring the Bech32 [BIP173](https://github.com/bitcoin/bips/blob/master/bip-0173.mediawiki).


## License [MIT](LICENSE)
