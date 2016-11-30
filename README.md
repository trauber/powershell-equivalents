# powershell-equivalents
Stay sane in a gui wonderland.

## diff

```powershell
compare-object (get-content file1.txt) (get-content file2.txt))
```

## grep



## sort

```powershell
get-content file.txt | sort-object | get-unique
```


## uniq
