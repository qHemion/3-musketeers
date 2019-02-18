# Cash
>the currency converter library

![a_dollar](https://cdn.discordapp.com/attachments/406127680459767808/547042233870712875/US_one_dollar_bill2C_obverse2C_series_2009.png)

# Presentation

  - Cash is a simple node library that is used to convert currencies.
  - It requires an internet connection
  - It uses the [Exchange rate API][api] to get the latest news about the change rate
  - It can convert to [many currencies]

## Installation

```sh
❯ npm install
```

### Getting started :

Usage
	```
		$ cash <amount> <from> <to>
		$ cash <options>
	```

Options
    ```
		--set -s 			Set default currencies
	```

Examples
		``$ cash 10 usd eur pln``
		``$ cash --set usd aud``




[api]: <https://api.exchangeratesapi.io/latest>
[many currencies]: <lib/currencies.json>