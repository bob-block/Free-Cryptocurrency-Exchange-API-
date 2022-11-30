# Free-Cryptocurrency-Exchange-API-
Cryptocurrencies that have entered our lives since 2009 have spread around the world in a short period because they are not affiliated with any authority and are anonymous. Today, especially in developed countries, spending is mostly done with digital money rather than paper money. Digital money stands for paper money, which is stored electronically and has transferable properties. Although there are nearly a thousand different cryptocurrencies today, the exact number is unknown.
Block.cc included 500+ exchanges, 10,000+ currencies, 28,000+ trading pairs, and 1000+ business users. It covers multi-dimensional data such as real-time price, historical transactions, currency information, K-line data, legal currency exchange rate, transaction depth, news flash, and block data.

Example request:

(1) Get currency price
curl -X GET \
  'https://data.block.cc/api/v3/price?slug=bitcoin,filecoin'
Response:
   [
  {
    "s": "bitcoin",
    "S": "BTC",
    "T": 1564201016247,
    "u": 10254.613,
    "b": 1,
    "a": 66180.407,
    "v": 663551832.77,
    "ra": 68260.277,
    "rv": 684890110,
    "m": 182193710000,
    "c": 0.0111,
    "h": 10254,
    "l": 10254,
    "cw": 0.0111,
    "hw": 10254,
    "lw": 10254,
    "cm": 0.0111,
    "hm": 10254,
    "lm": 10254,
    "ha": 10254,
    "la": 10254
  }
]

(2) Get currency historical price

curl -X GET \ 'https://data.block.cc/api/v3/price/history?slug=bitcoin' 
Response:

[
 {
 "T": 1577758200000,
 "u": 7260.6657,
 "b": 1.0,
 "a": 1501274.4,
 "v": 1.087066438855E10,
 "m": 1.087066438855E10
 },
 {
 "T": 1577691000000,
 "u": 7397.4515,
 "b": 1.0,
 "a": 1495078.8,
 "v": 1.09867723397E10,
 "m": 1.132314561458E10
 },
 {
 "T": 1577724600000,
 "u": 7253.9142,
 "b": 1.0,
 "a": 1559626.1,
 "v": 1.132314561458E10,
 "m": 1.132314561458E10
  }
]

(3) Get the exchange rate, the exchange rate of this interface is based on USD

curl -X GET \ 'https://data.block.cc/api/v3/exchange_rate' 
Response:

[
 {
 "c": "USD",
 "r": 1
 },
 { "c": "AED",
 "r": 3.6729
 },
 { "c": "AFN",
 "r": 78.31899
 },
 { "c": "ALL",
 "r": 111.601841
 },
 { "c": "AMD",
 "r": 477.853793
 } 
]

Conclusion

With the advantages of Cryptocurrency Exchange API services, businesses offer instant and historical data to their users in just milliseconds through their applications.
