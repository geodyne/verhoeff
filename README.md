


# Verhoeff Check



Find Verhoeff check digit
```

> var verhoeff = require('@skylab/verhoeff');
> var num = 78639;
> var checksum = verhoeff.checksum(num);
> console.log(checksum);
2

```


Verifying if a number is valid
```

> var verify = verhoeff.validate(786392);
undefined
> console.log(verify);
true
undefined
> 
> 


```

