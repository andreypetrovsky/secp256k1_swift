# secp256k1_swift
The secp256k1 curve is a part of Elliptic Swift library. The secp256k1 curve was constructed in a special non-random way which allows for especially efficient computation. As a result, it is often more than 30% faster than other curves if the implementation is sufficiently optimized. Also, unlike the popular NIST curves, secp256k1's constants were selected in a predictable way, which significantly reduces the possibility that the curve's creator inserted any sort of backdoor into the curve.

## Usage

Add to the Podfile
```
pod 'secp256k1_swift', '~> 0.1.0'
```
