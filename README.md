# Internationalization

## ISO (International Organization for Standardization)

### ISO 3166 Country Codes

- [ISO 3166 Country Codes](https://www.iso.org/iso-3166-country-codes.html)

### ISO 4217 Currency codes

- [ISO 4217 Currency codes](https://www.iso.org/iso-4217-currency-codes.html)

### ISO 639 Language Codes

- [ISO 639 Language codes](https://www.iso.org/iso-639-language-codes.html)

### ISO 8601 Date & Time Format

- [ISO 8601 Date & Time Format](https://www.iso.org/iso-8601-date-and-time-format.html)

## IETF BCP 47 Language Tag
> An IETF BCP 47 language tag is a 
> standardized code or tag that is 
> used to identify human languages in 
> the Internet. The tag structure has 
> been standardized by the Internet 
> Engineering Task Force (IETF) in 
> Best Current Practice (BCP) 47; the 
> subtags are maintained by the IANA 
> Language Subtag Registry.

## IANA Language Subtag Registry
Contains language tags (abbreviated language codes) as defined by the Internet Engineering Task Force (IETF).
- [npm language-subtag-registry](https://www.npmjs.com/package/language-subtag-registry)

## Global Intl Object

### Locale ID
Case-sensitive string that consists of the following (separated by hyphens):

1. a language subtag,
2. (optionally) a script subtag,
3. (optionally) a region (or country) subtag,
4. (optionally) one or more variant subtags (all of which must be unique),
5. (optionally) one or more BCP 47 extension sequences, and
6. (optionally) a private-use extension sequence

> Each subtag and sequence are separated by hyphens. 
> Locale identifiers are case-insensitive ASCII. However, 
> it's conventional to use title case (the first letter 
> is capitalized, successive letters are lower case) for 
> script subtags, upper case for region subtags, and 
> lower case for everything else. 
> 
> For example:
> 
> - "hi": Hindi (language)
> - "de-AT": German (language) as used in Austria (region)
> - "zh-Hans-CN": Chinese (language) written in simplified characters (script) as used in China (region)
> - "en-emodeng": English (language) in the "Early modern English" dialect (variant)

### Notes
- Not a constructor, all properties are static

## i18next

- i18next
- react-i18next
- i18next-http-backend
- i18next-browser-languagedetector

## Locize API
- [Fetch available languages](https://docs.locize.com/integration/api#fetch-the-available-languages)
- [Report missing translations](https://docs.locize.com/integration/api#missing-translations)

# Links
- [Global Intl Object](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Intl)
- [IANA Language Subtag Registry](https://www.iana.org/assignments/language-subtag-registry/language-subtag-registry)
- [Docs for react-i18next](https://react.i18next.com/)
- [The history of i18next](https://www.i18next.com/misc/the-history-of-i18next)
- [Translate React Apps With Localize](https://help.localizejs.com/docs/react?utm_term=react%20internationalization&utm_campaign=IntegrationsCompetitors&utm_source=adwords&utm_medium=ppc&hsa_acc=6638313475&hsa_cam=19324393370&hsa_grp=144047416265&hsa_ad=642064858998&hsa_src=g&hsa_tgt=kwd-340526291674&hsa_kw=react%20internationalization&hsa_mt=p&hsa_net=adwords&hsa_ver=3&gad=1&gclid=Cj0KCQjwnMWkBhDLARIsAHBOftq1mQeu5B3s1caELg5qd2IXSNqHbm7F0Cec3H5kjZ4XTvmA1Nc4p10aAuUZEALw_wcB)
- [Locize Docs](https://docs.locize.com/)
- [Locize API](https://docs.locize.com/integration/api)
- [Internationalization (i18n) in React using hooks](https://levelup.gitconnected.com/internationalization-i18n-in-react-using-hooks-62e1262c2c51)
