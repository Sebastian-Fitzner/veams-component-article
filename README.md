<p align="right">
<a href="https://badge.fury.io/js/%40veams%2Fcomponent-article"><img src="https://badge.fury.io/js/%40veams%2Fcomponent-article.svg" alt="npm version" height="18"></a>
    <a href="https://gitter.im/Sebastian-Fitzner/Veams?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge"><img src="https://badges.gitter.im/Sebastian-Fitzner/Veams.svg" alt="Gitter Chat" /></a>
</p>

# Article

## Description

The article component is a `wrap-with` partial to give you the possibility to put in every content you need. 

----------- 

## Installation 

### Installation with Veams

```bash
veams install component article
```
``` bash 
veams -i c article
```

----------- 

## Fields

### `article-usage.hbs`

The partial is a `{{#wrapWith}}` helper. Documentation for [wrapWith](https://github.com/Sebastian-Fitzner/mangony-hbs-helper-wrap-with) helper.

### `article.hbs`

#### Settings

| Parameter | Type | Value | Description |
|:--- | :---: |:---: | :--- |
| settings.articleContextClass | String | `default` | Context class of component. |
| settings.articleClasses | String |  | Modifier classes for component. |
| settings.articleHeader.articleHeaderClasses | String |  | Classes for header element. |
| settings.articleContentClasses | String |  | Classes for content div. |
| settings.articleFooter.articleFooterClasses | String |  | Classes for footer element. |


#### Content 

| Parameter | Type | Description |
|:--- | :---: | :--- |
| content.articleHeader | Object | Object which contains multiple elements |
| content.articleHeader.articleDate | String | Date string |
| content.articleHeader.articleDatetime | String | Date attribute |
| content.articleHeader.articleH1 | String | Header H1 |
| content.articleHeader.articleH2 | String | Header H2 |
| content.articleHeader.articleH3 | String | Header H3 |
| content.articleHeader.articleIntro | String | Header Intro |
| content.articleFooter | Object | Object which contains multiple elements |
| content.articleFooter.articleFooterLink | String | Footer link |
