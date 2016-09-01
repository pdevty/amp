# AMP

AMP is a simple AMP (Accelerated Mobile Pages) material design theme for [Hugo](http://gohugo.io/).

![](https://github.com/pdevty/amp/blob/master/images/tn.png)

## Features

- Simple AMP (Accelerated Mobile Pages) Material Design by [ampproject](https://www.ampproject.org/)
- Google Analytics (optional)
- Pagination
- Twitter, Facebook, GitHub, Google+, LinkedIn links (optional)
- Tags (optional)
- Categories (optional)

## Installation

```shell
$ cd themes
$ git clone https://github.com/pdevty/amp
```

## Usage

```shell
$ hugo server -t amp
```

## Configuration

config.toml

```toml
theme="amp"
baseurl = "Your Site URL"
title = "Your Site Title"
paginate = 10
copyright = "© 2016 Copyright Text"
canonifyurls = true

# optional
[params]
  googleAnalyticsUserID = "Your Analytics User ID"

# optional
[social]
  twitter = "Your Twitter Name"
  github = "Your Github Name"
  facebook = "Your facebook Name"
  gplus = "Your Google+ profile name"
  linkedin = "Your LinkedIn Name"

# optinal
[permalinks]
  post = "/:year/:month/:day/:title/"
```

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
