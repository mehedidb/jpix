# jpix - Simple jQuery Tabs and Accordion

A lightweight script to active jquery tabs and accodion on you theme

## Initialize 

### for tabs
```
$('.element').pixiefyTabs();

```
### for accodion
```
$('.element').pixiefyAccordion();

```

## Extra options for tabs

```
$('.element').pixiefyTabs({
	activeClass : "current",
	activeContent: "current",
	dataAttr: "data-tab"
});

```
## Extra options for accodion

```
$('.element').pixiefyAccordion({
	openDefault: false,
	activeClass : "current",
	activeContent: "show",
	dataClass: "panel-heading"
});

```

You can pass multiple value in every function like
