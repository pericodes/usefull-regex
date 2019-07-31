# Credits Card regex
## Regex (regular expression) for matching credits cards in a text.

| Credit Card       | Regex           |Source          |
| ----------------- |:---------------:| :--------------:|
| Amex Card |  3[47][0-9]{13} | https://stackoverflow.com/questions/9315647/regex-credit-card-number-tests |
| BCGlobal |  (6541\|6556)[0-9]{12} | https://stackoverflow.com/questions/9315647/regex-credit-card-number-tests |
| Carte Blanche Card |  389[0-9]{11} | https://stackoverflow.com/questions/9315647/regex-credit-card-number-tests |
| Diners Club Card |  3(?:0[0-5]\|[68][0-9])[0-9]{11} | https://stackoverflow.com/questions/9315647/regex-credit-card-number-tests |
| Discover Card |  65[4-9][0-9]{13}\|64[4-9][0-9]{13}\|6011[0-9]{12}\|(622(?:12[6-9]\|1[3-9][0-9]\|[2-8][0-9][0-9]\|9[01][0-9]\|92[0-5])[0-9]{10}) | https://stackoverflow.com/questions/9315647/regex-credit-card-number-tests |
| Insta Payment Card |  63[7-9][0-9]{13} | https://stackoverflow.com/questions/9315647/regex-credit-card-number-tests |
| JCB Card |  (?:2131\|1800\|35\d{3})\d{11} | https://stackoverflow.com/questions/9315647/regex-credit-card-number-tests |
| KoreanLocalCard |  9[0-9]{15} | https://stackoverflow.com/questions/9315647/regex-credit-card-number-tests |
| Laser Card |  (6304\|6706\|6709\|6771)[0-9]{12,15} | https://stackoverflow.com/questions/9315647/regex-credit-card-number-tests |
| Maestro Card |  (5018\|5020\|5038\|6304\|6759\|6761\|6763)[0-9]{8,15} | https://stackoverflow.com/questions/9315647/regex-credit-card-number-tests |
| Mastercard |  (5[1-5][0-9]{14}\|2(22[1-9][0-9]{12}\|2[3-9][0-9]{13}\|[3-6][0-9]{14}\|7[0-1][0-9]{13}\|720[0-9]{12})) | https://stackoverflow.com/questions/9315647/regex-credit-card-number-tests |
| Solo Card |  (6334\|6767)[0-9]{12}\|(6334\|6767)[0-9]{14}\|(6334\|6767)[0-9]{15} | https://stackoverflow.com/questions/9315647/regex-credit-card-number-tests |
| Switch Card |  (4903\|4905\|4911\|4936\|6333\|6759)[0-9]{12}\|(4903\|4905\|4911\|4936\|6333\|6759)[0-9]{14}\|(4903\|4905\|4911\|4936\|6333\|6759)[0-9]{15}\|564182[0-9]{10}\|564182[0-9]{12}\|564182[0-9]{13}\|633110[0-9]{10}\|633110[0-9]{12}\|633110[0-9]{13} | https://stackoverflow.com/questions/9315647/regex-credit-card-number-tests |
| Union Pay Card |  (62[0-9]{14,17}) | https://stackoverflow.com/questions/9315647/regex-credit-card-number-tests |
| Visa Card |  4[0-9]{12}(?:[0-9]{3}) | https://stackoverflow.com/questions/9315647/regex-credit-card-number-tests |
| Visa Master Card |  (?:4[0-9]{12}(?:[0-9]{3})?\|5[1-5][0-9]{14}) | https://stackoverflow.com/questions/9315647/regex-credit-card-number-tests |

## Validation
Some of this credits cards can be validated with this algothim [Luhn algorithm](https://en.wikipedia.org/wiki/Luhn_algorithm).
