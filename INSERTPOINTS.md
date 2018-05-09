## Usage

### Include: Page

``` hbs
{{! @INSERT :: START @id: article, @tag: component-partial }}
	{{#with article.variatons.default}}
		{{#wrapWith article settings=this.settings content=this.content}}
		    Far far away, behind the word mountains, far from the countries Vokalia and Consonantia, there live the blind texts. Separated they live in Bookmarksgrove right at the coast of the Semantics, a large language ocean.
		{{/wrapWith}}
	{{/with}}
	
{{! @INSERT :: END }}
```
