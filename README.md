<p align="center">
    <a href="https://badge.fury.io/bo/veams-component-article"><img src="https://badge.fury.io/bo/veams-component-article.svg" alt="Bower version" height="20"></a>
    <a href="https://gitter.im/Sebastian-Fitzner/Veams?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge"><img src="https://badges.gitter.im/Sebastian-Fitzner/Veams.svg" alt="Gitter Chat" /></a>
</p>

# Article

## Description

This blueprint is based on the blueprint of Veams-Components.

The article component is a `wrap-with` partial to give you the possibility to put in every content you need. 

----

## Fields

### General
- settings.articleContextClass {`String`} [default] - Just pass a string
- settings.articleClasses {`String`} - Modifier classes

### Header
- articleHeader {`Object`} - Object which contains multiple elements
- settings.articleHeader.articleHeaderClasses {`String`} - Class for header
- content.articleHeader.articleDate {`String`} - Date string
- content.articleHeader.articleDatetime {`String`} - Date attribute
- content.articleHeader.articleH1 {`String`} - Header H1
- content.articleHeader.articleH2 {`String`} - Header H2
- content.articleHeader.articleH3 {`String`} - Header H3
- content.articleHeader.articleIntro {`String`} - Header Intro

### Content
- settings.articleContentClasses {`String`} - Classes content div

### Footer
- articleFooter {`Object`} - Object which contains multiple elements
- settings.articleFooter.articleFooterClasses {`String`} - Class for footer element
- content.articleFooter.articleFooterLink {`String`} - Footer link