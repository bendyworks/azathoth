# Azathoth

Bendywork's [as-sane-as-possible][azathoth] JavaScript toolset.

  [azathoth]: http://en.wikipedia.org/wiki/Azathoth

## Principles

- *Observability:* you should be able to see what any portion of toolchain is
  doing
- *Locality:* developers should need to be aware of as little context as
  possible, any context should be explictly brought in.
- *Communicative:* feedback for user changes (e.g. compilation / testing)
  should happen as quickly as possible
- *Modernity:* our tooling should be kept up-to-date with the latest idioms and
  practicies of the JavaScript community while retaining stability
- *Tasteful:* use only abstractions with a high specific impulse; no Faustian
  deals

## Tooling

- [Node and NPM][node] for server-side tooling package management
- [Bower][bower] for client-side package management
- [Mocha][mocha] for testing
- [Grunt][grunt] for task-running

  [node]: https://nodejs.org/
  [bower]: http://bower.io/
  [mocha]: http://mochajs.org/
  [grunt]: http://gruntjs.com/

## Libraries

- [immutable.js][immutable] for immutable data structures
- [transit.js][transit] for advanced data serialization
- [mori.js][mori] for advanced functional JavaScript features (beyond
  Underscore or Lowdash)

  [immutable]: https://github.com/facebook/immutable-js
  [transit]: https://github.com/cognitect/transit-js
  [mori]: https://github.com/swannodette/mori
