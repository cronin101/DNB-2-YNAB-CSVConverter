DNB + YNAB Tools
=======================

Converts the DNB CSV format into that required for importing into YNAB4

##Usage

```zsh
# Convert statement CSV downloaded from dnb.no into YNAB importable format.
$ ./dnb_csv_mangler maanedtransaksjonliste-aug.csv > august.csv

# Same as the above but only output transactions past the given date
$ ./transactions_since "last monday" transaksjonliste.txt
```
