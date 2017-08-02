### Include: Page

``` hbs
{{! @INSERT :: START @id: toggler, @tag: component-partial }}
{{#with toggler-bp}}
	{{#wrapWith "c-toggler"}}
		Wrapped with markup from toggler.
	{{/wrapWith}}
{{/with}}
{{! @INSERT :: END }}
```

### Include: SCSS
``` scss
// @INSERT :: START @tag: scss-self-contained-import //
@import "../components/toggler/scss/_c-toggler";
// @INSERT :: END
```

### Include: JavaScript

#### Import
``` js
// @INSERT :: START @tag: js-self-contained-import //
import Toggler from '../components/toggler/js/toggler';
// @INSERT :: END
```

#### Initializing in Veams V5
``` js
// @INSERT :: START @tag: js-init-v5 //
	,
	// Init Toggler //
	{
		domName: 'toggler',
		module: Toggler,
	}
// @INSERT :: END
```