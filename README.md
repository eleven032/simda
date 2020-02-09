# [Simda.js](https://www.npmjs.com/package/simda)

A light-weight alternative (in ES6+) of [Ramda.js](https://ramdajs.com/)

### Installation

```shell
npm i simda
```

### Usage

```js
import * as S from 'simda'

const newObj = S.assocPath(['a', 1, 'c'], 999)({a: [{b: 111}]})
console.log(newObj) // => {a:[{b:111},{c:999}]}
```

### Functions

- [x] [**_arity**](src/internal/_arity.js)
- [x] [_complement](src/internal/_complement.js)
- [x] [**_curry1**](src/internal/_curry1.js)
- [x] [**_curry2**](src/internal/_curry2.js)
- [x] [**_curry3**](src/internal/_curry3.js)
- [x] [_filter](src/internal/_filter.js)
- [x] [**_has**](src/internal/_has.js)
- [x] [_identity](src/internal/_identity.js)
- [x] [**_isArguments**](src/internal/_isArguments.js)
- [x] [_isArray](src/internal/_isArray.js)
- [x] [**_isArrayLike**](src/internal/_isArrayLike.js)
- [x] [_isFunction](src/internal/_isFunction.js)
- [x] [**_isInteger**](src/internal/_isInteger.js)
- [x] [_isObject](src/internal/_isObject.js)
- [x] [_isString](src/internal/_isString.js)
- [x] [**_map**](src/internal/_map.js)
- [x] [**_pipe**](src/internal/_pipe.js)
- [x] [**_reduce**](src/internal/_reduce.js)
- [x] [_toString](src/internal/_toString.js)
- [x] [add](src/add.js)
- [x] [always](src/always.js)
- [x] [ascend](src/ascend.js)
- [x] [assoc](src/assoc.js)
- [x] [**assocPath**](src/assocPath.js)
- [x] [concat](src/concat.js)
- [x] [defaultTo](src/defaultTo.js)
- [x] [descend](src/descend.js)
- [x] [**empty**](src/empty.js)
- [x] [F](src/F.js)
- [x] [**filter**](src/filter.js)
- [x] [flatten](src/flatten.js)
- [x] [fromPairs](src/fromPairs.js)
- [x] [head](src/head.js)
- [x] [identity](src/identity.js)
- [x] [**is**](src/is.js)
- [x] [isFunction](src/isFunction.js)
- [x] [isNil](src/isNil.js)
- [x] [**isPlainObj**](src/isPlainObj.js)
- [x] [**keys**](src/keys.js)
- [x] [**map**](src/map.js) supported (val, key, list)=>{...}
- [x] [mergeRight](src/mergeRight.js)
- [x] [multiply](src/multiply.js)
- [x] [nth](src/nth.js)
- [x] [path](src/path.js)
- [x] [pathOr](src/pathOr.js)
- [x] [pick](src/pick.js)
- [x] [pickAll](src/pickAll.js)
- [x] [pickBy](src/pickBy.js)
- [x] [**pipe**](src/pipe.js)
- [x] [pluck](src/pluck.js)
- [x] [prop](src/prop.js)
- [x] [propOr](src/propOr.js)
- [x] [reduce](src/reduce.js)
- [x] [reject](src/reject.js)
- [x] [replace](src/replace.js)
- [x] [slice](src/slice.js)
- [x] [sort](src/sort.js)
- [x] [**sortBy**](src/sortBy.js)
- [x] [split](src/split.js)
- [x] [sum](src/sum.js)
- [x] [T](src/T.js)
- [x] [tail](src/tail.js)
- [x] [toLower](src/toLower.js)
- [x] [toPairs](src/toPairs.js)
- [x] [toUpper](src/toUpper.js)
- [x] [**trim**](src/trim.js)
- [x] [unnest](src/unnest.js)
- [x] [values](src/values.js)
- [x] [zipObj](src/zipObj.js)
