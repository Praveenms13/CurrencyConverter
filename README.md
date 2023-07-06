# Currency Converter Tool

This is a command-line tool that allows you to convert currencies using exchange rates from `exchangerate-api.com`.

## Prerequisites

Before using the tool, make sure you have the following:

- Python 3 installed on your system
- Requests library installed (`pip install requests`)

## Usage

```bash
cc [ --from=<from currency> ] [--to=<to currency>] [<amount>]

(or)

cc [ <from currency> <to currency> <amount>]
```
`
- ---from = `<from currency>` or -f = `<from currency>`: Specify the currency code to convert from.
- --to = `<to currency>` or -t=`<to currency>`: Specify the currency code to convert to.
- `<amount>`: The amount to convert.

## Examples
- cc --from=USD --to=EUR 100
- cc USD EUR 100
