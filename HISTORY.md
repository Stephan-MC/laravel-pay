## 1.8.1 - 2024-10-07
* Support laravel 11

## 1.8.0 - 2023-12-23
* Handle multiple MeSomb applications in the same Laravel project. You can now change applicationKey (accessKey and secretKey) on the fly.

## 1.7.0 - 2022-10-17 [BREAKING CHANGES]
* Integration of new security process in all MeSomb request base on MeSomb Signature
* All operation has been migrated into the package Hachther\MeSomb\Operation\Payment and Payment operation have renamed to Collect
