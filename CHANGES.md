CHANGES
=======

### 0.0.4 / Not Yet Released

  * [Changes](https://github.com/migrs/rack-server-pages/compare/v0.0.3...master)

  * Enhancement
    - Thread safety
    - Add instance variables info in `rubyinfo`

  * Bufix
    - Didn't work `Rack::ServerPages::Template.tilt=`
    - and rename to `Rack::ServerPages::Template.use_tilt`

  * Refactor
    - Create Filter class
    - Binding setup in own class method

  * Documents
    - Filters and Helpers
    - Add [CHAMGES.md](https://github.com/migrs/rack-server-pages/blob/master/CHAMGES.md) (this document)


### [0.0.3](https://github.com/migrs/rack-server-pages/tree/v0.0.3) / 2012-01-06

  * [Changes](https://github.com/migrs/rack-server-pages/compare/v0.0.2...v0.0.3)

  * Feature
    - Before/After Filters
    - Include Helpers

  * Enhancement
    - Binding class initialized at boot
    - `partial` accepts block
    - bundle update

  * Refactor
    - Move rubyinfo helper to other file


### [0.0.2](https://github.com/migrs/rack-server-pages/tree/v0.0.2) / 2012-01-01

  * [Changes](https://github.com/migrs/rack-server-pages/compare/v0.0.1...v0.0.2)

  * Bugfix
    - Didn't launch with ERBTemplate


### [0.0.1](https://github.com/migrs/rack-server-pages/tree/v0.0.1) / 2012-01-01

  * Initial Release

  * Feature
    - Serving dynamic pages (default: ERB)
    - Serving static files
    - Tilt support (optional)
    - Include a partial template
    - Layout template