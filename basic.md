[go to code4mk for better view](https://code4mk.org/javascript-developer/js/regex)

## basic

```js
/a/
// kamal is the developer of code4mk organization.
```

* [demo](https://regexr.com/3nnms)

## first

`^` tick means select from `first`

```js
/^ka/
// kamal is the developer of code4mk organization.
```

* [demo](https://regexr.com/3nnpj)


## last
`$` last position

```js
/ion$/
```

* [demo](https://regexr.com/3nnrf)


## dot

`dot` is decimal point.

* it count `space`  as a position.

```js
/..oper/
/.oper/
//kamal is the developer of code4mk organization.
```

* [demo](https://regexr.com/3nnsd)

## escape

`\` blackslash use for escape specialess (`{ } [ ] / \ + * . $ ^ | ?`)

```js
/\*al/
//kam*l is the developer of code4mk organization.
```


* [demo](https://regexr.com/3nnt5)

## plus

```js
/be+/
// be
// bee
// bebe
// beeeeeebee
// beee
```



* [ demo](https://regexr.com/3nnur)


## optional


```js
/colou?/
// color
// colour
```

* [demo](https://regexr.com/3no49)

## alternate

`|` pipe / or / alternate

```js
/red|blue/
// red
// blue
// green
```

* [ demo](https://regexr.com/3ns23)

---

* [previous](https://github.com/code4mk/lets-regex/blob/master/README.md)
* [Next](https://github.com/code4mk/lets-regex/blob/master/group-set.md)
