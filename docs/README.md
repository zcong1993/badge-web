# Badge Service

## Usage

```
https://badge1.zcong.moe/badge/:subject/:status/:color?style=for-the-badge
                              ──┬──  ───┬───  ──┬───  ──┬── ────┬──────
                                │        │       │        │       └─ Style (optional)
                                │        │       │        │
                                │       TEXT    TEXT    RGB / COLOR_NAME ( optional )
                                │
                             "badge" - default (static) badge generator
```

Available color names:

![](https://badge1.zcong.moe/badge/color/blue/blue)
![](https://badge1.zcong.moe/badge/color/cyan/cyan)
![](https://badge1.zcong.moe/badge/color/green/green)
![](https://badge1.zcong.moe/badge/color/yellow/yellow)
![](https://badge1.zcong.moe/badge/color/orange/orange)
![](https://badge1.zcong.moe/badge/color/red/red)
![](https://badge1.zcong.moe/badge/color/pink/pink)
![](https://badge1.zcong.moe/badge/color/purple/purple)
![](https://badge1.zcong.moe/badge/color/grey/grey)

custom hex colors:

![](https://badge1.zcong.moe/badge/color/FB9966/FB9966)
![](https://badge1.zcong.moe/badge/color/F596AA/F596AA)
![](https://badge1.zcong.moe/badge/color/A5DEE4/A5DEE4)
![](https://badge1.zcong.moe/badge/color/91989F/91989F)

Available style:

![](https://badge1.zcong.moe/badge/style/default/green)

![](https://badge1.zcong.moe/badge/style/falt/green?style=flat)

![](https://badge1.zcong.moe/badge/style/for-the-badge/green?style=for-the-badge)

## Examples

### github

|               Type | Badge                                                               | link                                                                                                     |
| -----------------: | :------------------------------------------------------------------ | :------------------------------------------------------------------------------------------------------- |
|                tag | ![](https://badge1.zcong.moe/github/tag/babel/babel)                | [/github/tag/babel/babel](https://badge1.zcong.moe/github/tag/babel/babel)                               |
|              stars | ![](https://badge1.zcong.moe/github/stars/babel/babel)              | [/github/stars/babel/babel](https://badge1.zcong.moe/github/stars/babel/babel)                           |
|              forks | ![](https://badge1.zcong.moe/github/forks/babel/babel)              | [/github/forks/babel/babel](https://badge1.zcong.moe/github/forks/babel/babel)                           |
|             issues | ![](https://badge1.zcong.moe/github/issues/babel/babel)             | [/github/issues/babel/babel](https://badge1.zcong.moe/github/issues/babel/babel)                         |
|            release | ![](https://badge1.zcong.moe/github/release/babel/babel)            | [/github/release/babel/babel](https://badge1.zcong.moe/github/release/babel/babel)                       |
|            license | ![](https://badge1.zcong.moe/github/license/babel/babel)            | [/github/license/babel/babel](https://badge1.zcong.moe/github/license/babel/babel)                       |
|           watchers | ![](https://badge1.zcong.moe/github/watchers/babel/babel)           | [/github/watchers/babel/babel](https://badge1.zcong.moe/github/watchers/babel/babel)                     |
|        open issues | ![](https://badge1.zcong.moe/github/open-issues/babel/babel)        | [/github/open-issues/babel/babel](https://badge1.zcong.moe/github/open-issues/babel/babel)               |
| open pull requests | ![](https://badge1.zcong.moe/github/open-pull-requests/babel/babel) | [/github/open-pull-requests/babel/babel](https://badge1.zcong.moe/github/open-pull-requests/babel/babel) |

### npm

|                 Type | Badge                                              | link                                                                   |
| -------------------: | :------------------------------------------------- | :--------------------------------------------------------------------- |
|              version | ![](https://badge1.zcong.moe/npm/version/babel)    | [/npm/version/babel](https://badge1.zcong.moe/npm/version/babel)       |
|     version (scoped) | ![](https://badge1.zcong.moe/npm/version/@vue/cli) | [/npm/version/@vue/cli](https://badge1.zcong.moe/npm/version/@vue/cli) |
|              license | ![](https://badge1.zcong.moe/npm/license/babel)    | [/npm/license/babel](https://badge1.zcong.moe/npm/license/babel)       |
|            downloads | ![](https://badge1.zcong.moe/npm/downloads/babel)  | [/npm/downloads/babel](https://badge1.zcong.moe/npm/downloads/babel)   |
|  downloads last week | ![](https://badge1.zcong.moe/npm/dw/babel)         | [/npm/dw/babel](https://badge1.zcong.moe/npm/dw/babel)                 |
| downloads last month | ![](https://badge1.zcong.moe/npm/dm/babel)         | [/npm/dm/babel](https://badge1.zcong.moe/npm/dm/babel)                 |
|  downloads last year | ![](https://badge1.zcong.moe/npm/dy/babel)         | [/npm/dy/babel](https://badge1.zcong.moe/npm/dy/babel)                 |

### packagephobia

|    Type | Badge                                                     | link                                                                                 |
| ------: | :-------------------------------------------------------- | :----------------------------------------------------------------------------------- |
| publish | ![](https://badge1.zcong.moe/packagephobia/publish/babel) | [/packagephobia/publish/babel](https://badge1.zcong.moe/packagephobia/publish/babel) |
| install | ![](https://badge1.zcong.moe/packagephobia/install/babel) | [/packagephobia/install/babel](https://badge1.zcong.moe/packagephobia/install/babel) |

### bundlephobia

| Type | Badge                                                 | link                                                                         |
| ---: | :---------------------------------------------------- | :--------------------------------------------------------------------------- |
| size | ![](https://badge1.zcong.moe/bundlephobia/size/babel) | [/bundlephobia/size/babel](https://badge1.zcong.moe/bundlephobia/size/babel) |
| gzip | ![](https://badge1.zcong.moe/bundlephobia/gzip/babel) | [/bundlephobia/gzip/babel](https://badge1.zcong.moe/bundlephobia/gzip/babel) |

### crates

|                   Type | Badge                                                | link                                                                       |
| ---------------------: | :--------------------------------------------------- | :------------------------------------------------------------------------- |
|                version | ![](https://badge1.zcong.moe/crates/version/cargo)   | [/crates/version/cargo](https://badge1.zcong.moe/crates/version/cargo)     |
|              downloads | ![](https://badge1.zcong.moe/crates/downloads/cargo) | [/crates/downloads/cargo](https://badge1.zcong.moe/crates/downloads/cargo) |
| downloads last version | ![](https://badge1.zcong.moe/crates/dl/cargo)        | [/crates/dl/cargo](https://badge1.zcong.moe/crates/dl/cargo)               |

### docker

|  Type | Badge                                                     | link                                                                                 |
| ----: | :-------------------------------------------------------- | :----------------------------------------------------------------------------------- |
| pulls | ![](https://badge1.zcong.moe/docker/pulls/library/ubuntu) | [/docker/pulls/library/ubuntu](https://badge1.zcong.moe/docker/pulls/library/ubuntu) |
| stars | ![](https://badge1.zcong.moe/docker/stars/library/ubuntu) | [/docker/stars/library/ubuntu](https://badge1.zcong.moe/docker/stars/library/ubuntu) |

### homebrew

|    Type | Badge                                                 | link                                                                         |
| ------: | :---------------------------------------------------- | :--------------------------------------------------------------------------- |
| version | ![](https://badge1.zcong.moe/homebrew/version/docker) | [/homebrew/version/docker](https://badge1.zcong.moe/homebrew/version/docker) |

### chrome extension

|         Type | Badge                                                                                        | link                                                                                                                                                       |
| -----------: | :------------------------------------------------------------------------------------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------- |
|      version | ![](https://badge1.zcong.moe/chrome-web-store/version/ckkdlimhmcjmikdlpkmbgfkaikojcbjk)      | [/chrome-web-store/version/ckkdlimhmcjmikdlpkmbgfkaikojcbjk](https://badge1.zcong.moe/chrome-web-store/version/ckkdlimhmcjmikdlpkmbgfkaikojcbjk)           |
|        users | ![](https://badge1.zcong.moe/chrome-web-store/users/ckkdlimhmcjmikdlpkmbgfkaikojcbjk)        | [/chrome-web-store/users/ckkdlimhmcjmikdlpkmbgfkaikojcbjk](https://badge1.zcong.moe/chrome-web-store/users/ckkdlimhmcjmikdlpkmbgfkaikojcbjk)               |
|        price | ![](https://badge1.zcong.moe/chrome-web-store/price/ckkdlimhmcjmikdlpkmbgfkaikojcbjk)        | [/chrome-web-store/price/ckkdlimhmcjmikdlpkmbgfkaikojcbjk](https://badge1.zcong.moe/chrome-web-store/price/ckkdlimhmcjmikdlpkmbgfkaikojcbjk)               |
|       rating | ![](https://badge1.zcong.moe/chrome-web-store/rating/ckkdlimhmcjmikdlpkmbgfkaikojcbjk)       | [/chrome-web-store/rating/ckkdlimhmcjmikdlpkmbgfkaikojcbjk](https://badge1.zcong.moe/chrome-web-store/rating/ckkdlimhmcjmikdlpkmbgfkaikojcbjk)             |
|        stars | ![](https://badge1.zcong.moe/chrome-web-store/stars/ckkdlimhmcjmikdlpkmbgfkaikojcbjk)        | [/chrome-web-store/stars/ckkdlimhmcjmikdlpkmbgfkaikojcbjk](https://badge1.zcong.moe/chrome-web-store/stars/ckkdlimhmcjmikdlpkmbgfkaikojcbjk)               |
| rating count | ![](https://badge1.zcong.moe/chrome-web-store/rating-count/ckkdlimhmcjmikdlpkmbgfkaikojcbjk) | [/chrome-web-store/rating-count/ckkdlimhmcjmikdlpkmbgfkaikojcbjk](https://badge1.zcong.moe/chrome-web-store/rating-count/ckkdlimhmcjmikdlpkmbgfkaikojcbjk) |

### pypi

|    Type | Badge                                          | link                                                           |
| ------: | :--------------------------------------------- | :------------------------------------------------------------- |
| version | ![](https://badge1.zcong.moe/pypi/version/pip) | [/pypi/version/pip](https://badge1.zcong.moe/pypi/version/pip) |
| license | ![](https://badge1.zcong.moe/pypi/license/pip) | [/pypi/license/pip](https://badge1.zcong.moe/pypi/license/pip) |

### rubygems

|                   Type | Badge                                             | link                                                                 |
| ---------------------: | :------------------------------------------------ | :------------------------------------------------------------------- |
|                version | ![](https://badge1.zcong.moe/gem/version/rails)   | [/gem/version/rails](https://badge1.zcong.moe/gem/version/rails)     |
|                   name | ![](https://badge1.zcong.moe/gem/name/rails)      | [/gem/name/rails](https://badge1.zcong.moe/gem/name/rails)           |
|              downloads | ![](https://badge1.zcong.moe/gem/downloads/rails) | [/gem/downloads/rails](https://badge1.zcong.moe/gem/downloads/rails) |
| downloads last version | ![](https://badge1.zcong.moe/gem/dv/rails)        | [/gem/dv/rails](https://badge1.zcong.moe/gem/dv/rails)               |

### travis

|           Type | Badge                                                | link                                                                       |
| -------------: | :--------------------------------------------------- | :------------------------------------------------------------------------- |
|          build | ![](https://badge1.zcong.moe/travis/babel/babel)     | [/travis/babel/babel](https://badge1.zcong.moe/travis/babel/babel)         |
| build (branch) | ![](https://badge1.zcong.moe/travis/babel/babel/6.x) | [/travis/babel/babel/6.x](https://badge1.zcong.moe/travis/babel/babel/6.x) |

### circleci

|           Type | Badge                                                             | link                                                                                   |
| -------------: | :---------------------------------------------------------------- | :------------------------------------------------------------------------------------- |
|          build | ![](https://badge1.zcong.moe/circleci/github/nuxt/nuxt.js)        | [/circleci/github/nuxt/nuxt.js](https://badge1.zcong.moe/circleci/github/nuxt/nuxt.js) |
| build (branch) | ![](https://badge1.zcong.moe/circleci/github/nuxt/nuxt.js/master) | [/circleci/nuxt/nuxt.js/master](https://badge1.zcong.moe/travis/nuxt/nuxt.js/master)   |

### codecov

|              Type | Badge                                                        | link                                                                                       |
| ----------------: | :----------------------------------------------------------- | :----------------------------------------------------------------------------------------- |
|          covarage | ![](https://badge1.zcong.moe/codecov/github/babel/babel)     | [/codecov/github/babel/babel](https://badge1.zcong.moe/codecov/github/babel/babel)         |
| covarage (branch) | ![](https://badge1.zcong.moe/codecov/github/babel/babel/6.x) | [/codecov/github/babel/babel/6.x](https://badge1.zcong.moe/codecov/github/babel/babel/6.x) |

### opencollective

|          Type | Badge                                                           | link                                                                                             |
| ------------: | :-------------------------------------------------------------- | :----------------------------------------------------------------------------------------------- |
|       backers | ![](https://badge1.zcong.moe/opencollective/backers/vuejs)      | [/opencollective/backers/vuejs](https://badge1.zcong.moe/opencollective/backers/vuejs)           |
|  contributors | ![](https://badge1.zcong.moe/opencollective/contributors/vuejs) | [/opencollective/contributors/vuejs](https://badge1.zcong.moe/opencollective/contributors/vuejs) |
|       balance | ![](https://badge1.zcong.moe/opencollective/balance/vuejs)      | [/opencollective/balance/vuejs](https://badge1.zcong.moe/opencollective/balance/vuejs)           |
| yearly income | ![](https://badge1.zcong.moe/opencollective/yearly/vuejs)       | [/opencollective/yearly/vuejs](https://badge1.zcong.moe/opencollective/yearly/vuejs)             |
