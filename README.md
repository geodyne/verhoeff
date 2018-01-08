


# Verhoeff Check



Find Verhoeff check digit


###checksum(number)

returns checksum digit for a number

```

> var verhoeff = require('@skylab/verhoeff');
> var num = 78639;
> var checksum = verhoeff.checksum(num);
> console.log(checksum);
2

```


Verifying if a number is valid


###validate(number)

verifies whether a number has a valid verhoeff checksum digit at end 


```

> var verify = verhoeff.validate(786392);
undefined
> console.log(verify);
true
undefined
> 
> 


```


### LICENSE

MIT License

