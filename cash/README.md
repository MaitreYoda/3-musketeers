# cash

cash
Features
Cash is a library which converts the amounts of money given in different currencies.
By default, if you put one currency

Getting started
Clone the project
npm install

Commands
Convert an amount of money from a currency to another one (or many) :
node index.js 
By default, if you don't give the final currency, it will convert into euro, US dollar and Pound Sterling.
If you don't give any parameter, it will convert from US dollar to euro and Pound Sterling.

--save, -s Save currencies as default currencies
--help, -h Display help message
--version, -v Display version number

Examples:
node index.js 1 CAD EUR 
result : 
√1.60 (CAD) Canadian Dollar

node index.js 100
result :
√80.85 (EUR) Euro
√71.65 (GBP) Pound Sterling node index.js 1 EUR CNY RUB
result :
√ 7.81 (CNY) Chinese Yuan
√ 70.49 (RUB) Russian Rouble

Currencies allowed
"AUD": "Australian Dollar",
"RUB": "Russian Rouble",
"EUR": "Euro",
"BGN": "Bulgarian Lev",
"BRL": "Real Brazilian",
"CAD": "Canadian Dollar",
"CHF": "Swiss Franc",
"CNY": "Chinese Yuan",
"CZK": "Czech Koruna",
"DKK": "Danish Krone",
"GBP": "Pound Sterling",
"HKD": "Hong Kong Dollar",
"HRK": "Croatian Kuna",
"HUF": "Hungarian Forint",
"IDR": "Indonesian Rupiah",
"ILS": "Israeli Shekel",
"INR": "Indian Rupee",
"JPY": "Japanes Yen",
"KRW": "South Korean Won",
"MXN": "Mexican Peso",
"MYR": "Malaysian Ringgit",
"NOK": "Norwegian Krone",
"PHP": "Philippine Peso",
"PLN": "Polish Zloty",
"RON": "Romanian New Leu",
"SEK": "Swedish Krona",
"SGD": "Singapore Dollar",
"THB": "Thai Baht",
"TRY": "Turkish Lira",
"USD": "US Dollar",
"ZAR": "South African Rand",
"NZD": "New Zealand Dollar"
Licence
None
