## Usage

### Include: Page

``` hbs
{{! @INSERT :: START @id: toggler, @tag: component-partial }}
{{#with toggler-bp}}
	{{#wrapWith "toggler"}}
		Wrapped with markup from toggler.
	{{/wrapWith}}
{{/with}}
{{! @INSERT :: END }}
```

### Include: JavaScript

#### Initializing in Veams V5

``` js
// @INSERT :: START @tag: js-init-v5 //
	// Init Toggler
    Veams.modules.add({ namespace: 'toggler', module: Toggler });
// @INSERT :: END
```