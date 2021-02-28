# studious-octo-enigma
rust tool. generate password.

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
