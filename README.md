# @wonderbot/ms

> Millisecond conversion utility
>
> 밀리초 변환 유틸리티

Forked from [Naval-Base/ms](https://github.com/Naval-Base/ms). Korean Version.

## Features

- Simply works.
- (+) Supports Korean.

## Install

```bash
npm i install @naval-base/ms
```

## Usage

```js
ms('2일')  // 172800000
ms('1d')      // 86400000
ms('10h')     // 36000000
ms('2.5 hrs') // 9000000
ms('2시간')      // 7200000
ms('1m')      // 60000
ms('5초')      // 5000
ms('1y')      // 31557600000
ms('100')     // 100
ms('-3 days') // -259200000
ms('-1시간')     // -3600000
ms('-200')    // -200
```

### 한국어

```js
ms(60000)             // "1분"
ms(2 * 60000)         // "2분"
ms(-3 * 60000)        // "-3분"
ms(ms('10 hours'))    // "10시간"
```

### English

```js
ms(60000, true)             // "1 minute"
ms(2 * 60000, true)         // "2 minutes"
ms(-3 * 60000, true)        // "-3 minutes"
ms(ms('10 hours'), true)    // "10 hours"
```

## Author

### Original

**@naval-base/ms** © [iCrawl](https://github.com/iCrawl), Released under the [MIT](https://github.com/iCrawl/kaori/blob/master/LICENSE) License.  
Authored and maintained by iCrawl.

> Twitter [@iCrawlToGo](https://twitter.com/iCrawlToGo)

### Rewrited

**@wonderbot/ms** [wonderlandpark](https://github.com/wonderlandpark)

Rewrited for Korean.
