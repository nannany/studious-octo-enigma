# studious-octo-enigma
Rust tool to generate password.

# Command Line Options

## -s --size

Define password length.

## -c --complexity

You can select "hard" or "normal". (Default is normal)  
"normal" mode uses [0-9a-zA-Z].  
"hard" mode uses [0-9a-zA-Z] and words listed below.

```
!#$%&()=|.,;[]/<>:@?_'"\];
```

## Example

```
C:\Users\nanna\.ghq\github.com\nannany\studious-octo-enigma\target\debug>pgen -s 15
xXB2MQmPe5fR2YH

C:\Users\nanna\.ghq\github.com\nannany\studious-octo-enigma\target\debug>pgen -s 15 -c hard
B>GiCTp=@%]P[BN
```

