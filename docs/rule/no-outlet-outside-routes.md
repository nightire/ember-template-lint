## no-outlet-outside-routes

`{{outlet}}` is used to specify locations into which routes may be rendered. Typically, to keep routing clear only
route templates should make use of `{{outlet}}`. Using `{{outlet}}` outside of a route template, e.g. in a component
 or a partial, will often lead to unexpected rendering locations for child routes.

This rule forbids usage of the following except in routes.

```hbs
{{outlet}}
```
