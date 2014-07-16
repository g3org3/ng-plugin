#ng-plugin v1.0.2

##Angular plugin

```html
<script src='ng-plugin.js'></script>
<script>
	var app = angular.module.('myApp', ['g3org3']);
</script>
```
##Directives
```html
<navbar title='My Title' theme='default' type='static' href='#' ng-theme='variable'></navbar>
<container></container>
<view></view>
{{ expr | fromNow }} //ng filter
```

###Extra:
for the fromNow ng-filter you need moment.js
```shell
$ bower install moment
```
or from http://momentjs.com/
