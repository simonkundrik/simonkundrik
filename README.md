# Hi, I'm Simon

Computer Science graduate (University of Essex), based in Colchester, UK. I find and fix correctness bugs in widely used open-source libraries, and I build small ML and web projects that run on the device.

## Open source

60+ pull requests merged across 15+ projects. Most are bugs I found myself by checking a library against its spec or a large set of generated inputs, then fixed with a test that fails before and passes after.

- [brianvoe/gofakeit](https://github.com/brianvoe/gofakeit/pulls?q=is%3Apr+author%3Asimonkundrik+is%3Amerged): fake data that wasn't valid. ABA routing numbers, ISBN-10, ISIN and UPC check digits, SSN and EIN prefixes, Bitcoin addresses.
- [harrisiirak/cron-parser](https://github.com/harrisiirak/cron-parser/pulls?q=is%3Apr+author%3Asimonkundrik+is%3Amerged) and [Hexagon/croner](https://github.com/Hexagon/croner/pulls?q=is%3Apr+author%3Asimonkundrik+is%3Amerged): DST handling, strict validation of cron syntax.
- [quagmt/udecimal](https://github.com/quagmt/udecimal/pulls?q=is%3Apr+author%3Asimonkundrik+is%3Amerged): decimal parsing, binary unmarshalling and square-root edge cases.
- [omgovich/colord](https://github.com/omgovich/colord/pulls?q=is%3Apr+author%3Asimonkundrik+is%3Amerged), [tinycolor](https://github.com/scttcper/tinycolor/pull/275), [react-colorful](https://github.com/omgovich/react-colorful/pulls?q=is%3Apr+author%3Asimonkundrik+is%3Amerged): rounding of exact halves in colour conversions.
- [websockets/ws](https://github.com/websockets/ws/pull/2352), [vuejs/core](https://github.com/vuejs/core/pull/16161), [faker-js/faker](https://github.com/faker-js/faker/pull/4257), [validator.js](https://github.com/validatorjs/validator.js/pull/2814): smaller fixes in larger projects.

I use AI tools like Claude Code day to day. Nothing goes into a PR until it has a failing test that now passes and I can explain why.

## Projects

- [plate-vision](https://github.com/simonkundrik/plate-vision): estimates meal calories from one photo, entirely on the device. PyTorch exported to ONNX, running on Android and in the browser, with calibrated uncertainty ranges instead of false precision.
- [kindred](https://github.com/simonkundrik/kindred): a pet-matching quiz that matches on temperament and what your life can sustain, not on looks. Runs in the browser, no account needed.
- [tuore-app](https://github.com/simonkundrik/tuore-app): a meal-planning PWA that builds recipes from groceries actually in stock at a local supermarket, with live prices.

## Find me

- [LinkedIn](https://www.linkedin.com/in/simon-kundrik-aa2b40204)
- Colchester, UK. Open to hybrid and remote graduate roles where getting the details right matters.
