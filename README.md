# xlsx2csv
Simple script for converting xlsx files to csv files commandline.
## Usage
```
            xlsx2csv [flags] <xlsx-to-be-read>

    flags:

    -c    Compact output: Whether to omit empty rows from output
    -d string
            Delimiter to use between fields (default ";")
    -i int
            Index of sheet to convert, zero based
    -l int
            Limit: Maximum of rows to extract (0 = unlimited)
    -o string
            filename to output to. -=stdout (default "-")
```

