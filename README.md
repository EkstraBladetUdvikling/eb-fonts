# EB Fonts

> EB fonts for SCSS and CSS


## Installation

```bash
npm install ebudvikling/eb-fonts --save
```


## Usage

Variables and maps:

```scss
@import "node_modules/eb-fonts/src/all.scss";
```

> The above also adds styling to the following html elements: **body**, **h1**, **h2**, **h3**, **h4**, **h5**, **h6**, **p**


### Only class styling

```scss
@import "node_modules/eb-fonts/src/all-onlyclassstyling.scss";
```



### Only size portion

from xxsmall to xxxlarge

```scss
@import "node_modules/eb-fonts/src/sizes/all.scss";
```

## Sizes

#### smartphone / mobile

Size name | eb size mapping | font-size
----------|-----------------|----------
xxsmall | ads | 7px
xsmall | caption | 10px
small | timestamp | 12px
medium | showmore | 15px
large | bodytext | 15px
xlarge | subtitle | 20px
xxlarge | quote | 20px
xxxlarge | title | 36px


#### desktop && tablet

Size name | eb size mapping | font-size
----------|-----------------|----------
xxsmall | ads | 10px
xsmall | caption | 12px
small | timestamp | 14px
medium | showmore | 16px
large | bodytext | 18px
xlarge | subtitle | 20px
xxlarge | quote | 30px
xxxlarge | title | 50px
