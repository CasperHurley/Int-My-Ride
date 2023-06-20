# Internationalization

## ISO (International Organization for Standardization)

> ISO allows free-of-charge use of its country, currency and 
> language codes from ISO 3166, ISO 4217 and ISO 639, respectively.
> 
> Users of ISO country codes have the option to subscribe to a paid 
> service that automatically provides updates and supplies the data 
> in formats* that are ready-to-use for a wide range of applications.
> 
> For more information, visit the ISO Store. 
>
> *(.csv, .xml and .xls formats)

### ISO 3166 Country Codes

[Docs](https://www.iso.org/iso-3166-country-codes.html)

### ISO 4217 Currency codes

#### Alphabetic Code
- Based on ISO 3166 codes for country names
- First two letters are country code
- (when possible) third is first letter of the currency name

#### Numeric Code
- Three digit code useful for when currency codes need to be understood in countries that do not use Latin scripts and for computerized systems
- Where possible, the three-digit numeric code is the same as the numeric country code.


[Docs](https://www.iso.org/iso-4217-currency-codes.html)

### ISO 639 Language Codes

Internationally recognized codes for the representation of more than 500 languages or language families

> This ISO standard can be applied across many types 
> of organization and situations. It’s invaluable for 
> bibliographic purposes, in libraries or information 
> management, including computerized systems, and for the 
> representation of different language versions on Websites.
> 
> Using a code(either 2, 3 or 4 letters long), rather 
> than the name of a language, has many benefits as some 
> cultures may have different names for the same language, 
> while some languages may share the same, or similar, names 
> even though they are unrelated.

ISO 639 is composed of five different parts:

- Part 1: ISO 639-1:2002 provides a 2-letter code that has been designed to represent most of the major languages of the world.
- Part 2: ISO 639-2:1998 provides a 3-letter code, which gives more possible combinations, so ISO 639-2:1998 can cover more languages.
- Part 3: ISO 639-3:2007 provides a 3-letter code and aims to give as complete a listing of languages as possible, including living, extinct and ancient languages.
- Part 4: ISO 639-4:2010 gives the general principles of language coding and lays down guidelines for the use of ISO 639.
- Part 5: ISO 639-5:2008 provides a 3-letter code for language families and groups (living and extinct).

[Docs](https://www.iso.org/iso-639-language-codes.html)

### ISO 8601 Date & Time Format

Standardized way of presenting:

- Date
- Time of day
- Coordinated Universal Time (UTC)
- Local time with offset to UTC
- Date and time
- Time intervals
- Recurring time intervals

[Docs](https://www.iso.org/iso-8601-date-and-time-format.html)

## IETF BCP 47 Language Tag
> An IETF BCP 47 language tag is a standardized code or tag that is 
> used to identify human languages in the Internet. The tag structure 
> has been standardized by the Internet Engineering Task 
> Force (IETF) in Best Current Practice (BCP) 47; the subtags are 
> maintained by the IANA Language Subtag Registry.

## IANA Language Subtag Registry
Contains language tags (abbreviated language codes) as defined by the Internet Engineering Task Force (IETF).
- [npm language-subtag-registry](https://www.npmjs.com/package/language-subtag-registry)

## Global Intl Object

### Static Properties

#### Intl.Collator
Constructor for collators, which are objects that enable language-sensitive string comparison.

##### .compare()
Getter function that compares two strings according to the sort order of this Intl.Collator object.

##### .resolvedOptions()
Returns a new object with properties reflecting the locale and collation options computed during initialization of the object.

```javasript   
const numberDe = new Intl.NumberFormat('de-DE');
const numberAr = new Intl.NumberFormat('ar');

console.log(numberDe.resolvedOptions().numberingSystem);
// Output: "latn"

console.log(numberAr.resolvedOptions().numberingSystem);
// Output: "arab"
```

[Try it](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Intl/Collator)

#### Intl.DateTimeFormat
Constructor for objects that enable language-sensitive date and time formatting.

#### Intl.DisplayNames
Constructor for objects that enable the consistent translation of language, region and script display names.

#### Intl.DurationFormat
Constructor for objects that enable locale-sensitive duration formatting.

#### Intl.ListFormat
Constructor for objects that enable language-sensitive list formatting.

#### Intl.Locale
Constructor for objects that represents a Unicode locale identifier.

##### Locale ID
Case-sensitive string that consists of the following (separated by hyphens):

1. language subtag,
2. (optionally) script subtag,
3. (optionally) region (or country) subtag,
4. (optionally) one or more variant subtags (all of which must be unique),
5. (optionally) one or more BCP 47 extension sequences, and
6. (optionally) private-use extension sequence

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

#### Intl.NumberFormat
Constructor for objects that enable language-sensitive number formatting.

#### Intl.PluralRules
Constructor for objects that enable plural-sensitive formatting and language-specific rules for plurals.

#### Intl.RelativeTimeFormat
Constructor for objects that enable language-sensitive relative time formatting.

#### Intl.Segmenter
Constructor for objects that enable locale-sensitive text segmentation.

### Notes
- Not a constructor, all properties are static

[Docs](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Intl)

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
