[url]: http://rinaldi.io
[zurb-foundation]: https://foundation.zurb.com
[cssnext]: http://cssnext.io
[myth]: http://www.myth.io
[spec]: https://drafts.csswg.org/mediaqueries/#mq-ranges

# media-queries [![Build Status](https://semaphoreci.com/api/v1/rafaelrinaldi/media-queries/branches/master/badge.svg)](https://semaphoreci.com/rafaelrinaldi/media-queries)

> CSS media queries based on [Zurb's Foundation][zurb-foundation] breakpoints

## Install

```sh
$ npm install media-queries --save
```

## Usage

```css
/* Import the library */
@import 'media-queries';

/* Then you can use available breakpoints */
@media (--large-up) {
  /* ... */
}
```

## Notes

Values are exported as [media queries ranges][spec], using `@custom-media`. That's a future specification so you'll probably need a `/(pre|post)\w?\-?processor/i`. Both [cssnext][cssnext] and [myth][myth] are really great options.

## License

MIT © [Rafael Rinaldi][url]
