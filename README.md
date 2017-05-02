# Regtxt specification

regtxt is an open format to add authentic company information to a DNS zone file. The information stored can be used in other systems to automatically use the stored information in their systems.

## Example

```
regtxt.regtxt.org	TXT	vatin=NL123456789B00; cc=12345678; iban=NL01BANK123456789;
regtxt.regtxt.org	TXT	bic=BANK2B;
```

`vatin` the companies VAT number

`cc` the companies Chamber of Commerce number

`iban` The Internation Bank Account Number for the company

`bic` The Bank Identifier Code of the IBAN above

## Origins

regtxt was an idea that won the `Doing business` track at the Dutch Open Hackathon 2016 in Rotterdam. The idea was build and pitched by [webpatser](http://github.com/webpatser).
