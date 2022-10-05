# usage

supported languages: `ar`, `bn`, `de`, `en`, `es`, `fr`, `hi`, `it`, `jp`, `ko`, `pt`, `ru`, `zh-cn`, `zh-hk`, `zh-tw`

alpha-2 code to country name
`a22country(a2, lang="en", codes=false)`

alpha-3 code to country name
`a32country(a3, lang="en", codes=false)`

numeric code to country name
`num2country(num, lang="en", codes=false)`

# test
```js
console.log(a22country("AF"));
console.log(a22country("AF", "ar"));
console.log(a22country("AF", "bn"));
console.log(a22country("AF", "de"));
console.log(a22country("AF", "en"));
console.log(a22country("AF", "es"));
console.log(a22country("AF", "fr"));
console.log(a22country("AF", "hi"));
console.log(a22country("AF", "it"));
console.log(a22country("AF", "jp"));
console.log(a22country("AF", "ko"));
console.log(a22country("AF", "pt"));
console.log(a22country("AF", "ru"));
console.log(a22country("AF", "zh-cn"));
console.log(a22country("AF", "zh-hk"));
console.log(a22country("AF", "zh-tw"));
console.log(a22country("AF", "zh-tw", true));
console.log(a22country("AF", "zh-tw", false));
console.log("-----");
console.log(a32country("ALA"));
console.log(a32country("ALA", "ar"));
console.log(a32country("ALA", "bn"));
console.log(a32country("ALA", "de"));
console.log(a32country("ALA", "en"));
console.log(a32country("ALA", "es"));
console.log(a32country("ALA", "fr"));
console.log(a32country("ALA", "hi"));
console.log(a32country("ALA", "it"));
console.log(a32country("ALA", "jp"));
console.log(a32country("ALA", "ko"));
console.log(a32country("ALA", "pt"));
console.log(a32country("ALA", "ru"));
console.log(a32country("ALA", "zh-cn"));
console.log(a32country("ALA", "zh-hk"));
console.log(a32country("ALA", "zh-tw"));
console.log(a32country("ALA", "zh-tw", true));
console.log(a32country("ALA", "zh-tw", false));
console.log("-----");
console.log(num2country("008"));
console.log(num2country("008", "ar"));
console.log(num2country("008", "bn"));
console.log(num2country("008", "de"));
console.log(num2country("008", "en"));
console.log(num2country("008", "es"));
console.log(num2country("008", "fr"));
console.log(num2country("008", "hi"));
console.log(num2country("008", "it"));
console.log(num2country("008", "jp"));
console.log(num2country("008", "ko"));
console.log(num2country("008", "pt"));
console.log(num2country("008", "ru"));
console.log(num2country("008", "zh-cn"));
console.log(num2country("008", "zh-hk"));
console.log(num2country("008", "zh-tw"));
console.log(num2country("008", "zh-tw", true));
console.log(num2country("008", "zh-tw", false));
```

output

```
Afghanistan
أفغانستان
আফগানিস্তান
Afghanistan
Afghanistan
Afganistán
AFGHANISTAN
अफगानिस्तान
Afghanistan
アフガニスタン
아프가니스탄
Afeganistão
Афганистан
阿富汗
阿富汗
阿富汗
[ '阿富汗', 'AF', 'AFG', '004' ]
阿富汗
-----
Åland Islands
جزر أولاند
অলান্দ দ্বীপপুঞ্জ
Åland
Åland Islands
Åland
ÅLAND, ÎLES
Åland Islands
Isole Åland
オーランド諸島
올란드 제도
Aland, Ilhas
Аландские острова
奥兰
奧蘭
奧蘭
[ '奧蘭', 'AX', 'ALA', '248' ]
奧蘭
-----
Albania
ألبانيا
আলবেনিয়া
Albanien
Albania
Albania
ALBANIE
अल्बानिया
Albania
アルバニア
알바니아
Albânia
Албания
阿尔巴尼亚
阿爾巴尼亞
阿爾巴尼亞
阿爾巴尼亞
阿爾巴尼亞
[ '阿爾巴尼亞', 'AL', 'ALB', '008' ]
阿爾巴尼亞
```


# data source

- ar	[قائمة الدول حسب المعيار الدولي أيزو 3166-1 - ويكيبيديا](https://ar.wikipedia.org/wiki/%D9%82%D8%A7%D8%A6%D9%85%D8%A9_%D8%A7%D9%84%D8%AF%D9%88%D9%84_%D8%AD%D8%B3%D8%A8_%D8%A7%D9%84%D9%85%D8%B9%D9%8A%D8%A7%D8%B1_%D8%A7%D9%84%D8%AF%D9%88%D9%84%D9%8A_%D8%A3%D9%8A%D8%B2%D9%88_3166-1)
- bn	[আইএসও ৩১৬৬-১ - উইকিপিডিয়া](https://bn.wikipedia.org/wiki/%E0%A6%86%E0%A6%87%E0%A6%8F%E0%A6%B8%E0%A6%93_%E0%A7%A9%E0%A7%A7%E0%A7%AC%E0%A7%AC-%E0%A7%A7)
- de	[ISO-3166-1-Kodierliste – Wikipedia](https://de.wikipedia.org/wiki/ISO-3166-1-Kodierliste)
- es	[ISO 3166-1 - Wikipedia, la enciclopedia libre](https://es.wikipedia.org/wiki/ISO_3166-1)
- fr	[ISO 3166-1 — Wikipédia](https://fr.wikipedia.org/wiki/ISO_3166-1)
- hi	[आइएसओ ३१६६ - १ - विकिपीडिया](https://hi.wikipedia.org/wiki/%E0%A4%86%E0%A4%87%E0%A4%8F%E0%A4%B8%E0%A4%93_%E0%A5%A9%E0%A5%A7%E0%A5%AC%E0%A5%AC_-_%E0%A5%A7)
- it	[ISO 3166-1 - Wikipedia](https://it.wikipedia.org/wiki/ISO_3166-1)
- jp	[ISO 3166-1 - Wikipedia](https://ja.wikipedia.org/wiki/ISO_3166-1)
- ko	[ISO 3166-1 - 위키백과, 우리 모두의 백과사전](https://ko.wikipedia.org/wiki/ISO_3166-1)
- pt	[ISO 3166-1 – Wikipédia, a enciclopédia livre](https://pt.wikipedia.org/wiki/ISO_3166-1)
- ru	[ISO 3166-1 — Википедия](https://ru.wikipedia.org/wiki/ISO_3166-1)
- zh-cn	[ISO 3166-1 - 维基百科，自由的百科全书](https://zh.wikipedia.org/zh-cn/ISO_3166-1)
- zh-hk	[ISO 3166-1 - 維基百科，自由的百科全書](https://zh.wikipedia.org/zh-hk/ISO_3166-1)
- zh-tw	[ISO 3166-1 - 維基百科，自由的百科全書](https://zh.wikipedia.org/zh-tw/ISO_3166-1)
