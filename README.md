# Data on Chinese court system

### The Four-level court system

- the Supreme People's Court
- higher people's courts at the province level
- intermediate people's courts at the prefecture level
- primary courts at the county/district level

<img src="court-system.png" width="350">

* Specialized courts: the military, maritime, railway, intellectual property, and internet courts.

### Included Variables

- court names (lists scraped from [中国法院网](https://www.chinacourt.org/index.shtml))
- upper level court for appeal
- court codes scraped from [China Judgments Online](http://wenshu.court.gov.cn/). One court code may include multiple court names, because (1) changes in administrative boundaries and administrative divisions; (2) there are multiple ways to indicate the same court in Chinese (e.g., 民和县人民法院, 民和回族土族自治县人民法院, 青海省民和回族土族自治县人民法院).
- The court code is a three-character string: the first character can be used to identify the province, and the second character can be used to identify prefectures in the province. 
- Court code: if the last two digits are '0', higher courts; if only the last digit is '0',  intermediate courts. 
