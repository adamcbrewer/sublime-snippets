# Sublime Text Snippets
Sort your shortcut life out.

### JavaScript

#### [cl] console.log

```
console.log(${1:object});
```

#### [cd] console.dir

```
console.dir(${1:object});
```

#### [cg] console.group (expanded)

```
console.group("${1:groupName}");
${0}
console.groupEnd();
```

#### [cgc] console.groupCollapsed

```
console.groupCollapsed("${1:groupName}");
${0}
console.groupEnd();
```

### HTML

#### [ri] a responsive image wrapped in a ```<figure>``` element. Requires supporting CSS.

```
<figure class="${1:ri}">
	<img src="${2}" alt="${3}" />
<figure>
${0}
```


### PHP

#### [pr] print_r wrapped with ```<pre>``` tags

```js
echo '<pre>';
print_r(${1:object});
echo '</pre>';
```


### Credit

Thanks to [@jprichardson](http://github.com/jprichardson) for [his guide](https://github.com/jprichardson/sublime-js-snippets) and a little inspiration.
