# Bootstrap Tooltip Activator

Ember addon for Bootstrap tooltips.

## Installation

* `npm install bootstrap4-tooltip-activator --save-dev`

## Dependencies
* Bootstrap CSS & JS  
**Note: This addon does not install it automatically**

## Ember Compatibility Table

| Ember Version       	| Bootstrap Tooltip Activator Version 	|
| ----------------------| --------------------------------------|
| 1.8 through 2.6.1    	| 0.0.1 =< x < 0.1.1         			|
| 2.6.2 and beyond	   	| >=1.0.0                    			|

## Usage
* Everything that is wrapped inside the `bootstrap4-tooltip-activator` will apply the bootstrap tooltips
```handlebars
{{#bootstrap4-tooltip-activator}}
	<button
		data-toggle="First tip"
		data-placement="top"
		data-container="body"
		data-original-title="Some tip">
		First button
	</button>
	<button
		data-toggle="Second tip"
		data-placement="bottom"
		data-container=".some-selector"
		data-original-title="Another tip">
		Second button
	</button>
{{/bootstrap4-tooltip-activator}}
```
**Note**: make sure to use the `data-original-title` attribute and not `title`  

## License
MIT 
