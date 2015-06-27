#DNB + YNAB Tools
> Nå kan du se hvor pengene dine gikk.

#####Converts the DNB CSV format into that required for importing into YNAB4

--
#####NB: A re-written online version of this tool is now available - requiring no download or configuration.
[Try out the online version here!](http://cronin101.github.io/DNB2YNAB-TypeScript/)
--

##Usage

```zsh
# Convert statement CSV downloaded from dnb.no into YNAB importable format.
$ ./dnb_csv_mangler maanedtransaksjonliste-aug.csv > august.csv

# Same as the above but only output transactions past the given date
$ ./transactions_since "last monday" transaksjonliste.txt
```
