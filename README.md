# rust-passphrase
Passphrase generator.

## Passphrases are just better.
They are easier to remember and more secure

For more information, check https://www.useapassphrase.com

## How to use
Examples:   
1. Generate a passphrase with 4 captalized words:
    ```bash
    $ rust-passphrase -w 4 -c
    > Patrol-Blandness-Professor-Five
    ```
1. Generate a passphrase with space as a separator:
    ```bash
    $ rust-passphrase -s " "
    > geiger sadness founder
    ```
1. Generate a captalized passphrase with a number at the end of one of the words:
    ```bash
    $ rust-passphrase -c -i
    > Create-Deluge1-Grandma
    ```
Usage:
```
Usage: rust-passphrase [OPTIONS]

Options:
  -w, --words <WORDS>          [default: 3]
  -c, --captalize              
  -s, --separator <SEPARATOR>  [default: -]
  -i, --include-number         
  -h, --help                   Print help information
  -V, --version                Print version information
```