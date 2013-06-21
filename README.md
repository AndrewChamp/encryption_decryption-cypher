#Encryption / Decryption Cypher

Easy encrypt / decrypt class with unique key.


##How To Use
```php
$cypher = new cypher('RANDOM_CODE_HERE');

$encypted = $cypher->encrypt('Some example text.');
//Output: 8sd72kjlasdjfklj23=

print $cypher->decrypt($encrypted);
//Output: Some example text.
```
