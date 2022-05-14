# enigma-cipher
 enigma encrypter

to install this repository
```
cd enigmaCiipher
mv enigmaCodeBook /usr/local/bin
mv enigmaCipher /usr/local/bin
```
run `enigmaCodeBook` for generating different enigma M3 machine settings for envery day

run `enigmaCipher -m <message>` to generate encrypted message for random settings, `enigmaCipher -r <reflector> -ro <rotor setting> -rs <ring setting> -rp <ring position> -p <plugboard setting> -m <message>` to encrypt for decrypt selected machine settings
