# Underdash.js

This is an experimental and provisional Underscore+Lodash merge repo. Nothing 
to see here, apart from sketches and wild ideas for the moment.

**Fleshing out a consensus API:**

## "Core" Functions

**Iteration**

* each (forEach)
* map
* mapValues
* reduce
* filter
* find
* where
* findWhere
* reject
* any (some)
* all (every)
* contains
* invoke
* pluck

**Grouping**

* groupBy
* indexBy
* countBy

**Arrays**

* rest
* compact
* flatten
* uniq

**Objects**

* keys
* allKeys
* values
* pairs
* invert
* create
* extend
* assign
* merge
* forIn
* forInRight
* forOwn
* forOwnRight
* pick
* defaults

**Functions**

* bind
* partial
* memoize
* throttle
* debounce
* compose

**Utility**

* noConflict
* times
* mixin
* iteratee
* chain
* value

## "More" Functions

**Iteration**

* transform
* reduceRight
* at
* sortBy (This should be functionally sortByAll — let's lose the thisArg)
* sortByOrder (But let's use 'asc' and 'desc' instead of truthy and falsy)
* shuffle
* sample
* toArray
* toPlainObject
* size
* partition

**Arrays**

* first
* last
* initial
* without
* union
* intersection
* difference
* xor
* zip
* unzip
* object
* indexOf
* lastIndexOf
* sortedIndex
* findIndex
* findLastIndex
* range
* slice
* fill
* chunk
* drop
* dropWhile
* dropRight
* dropRightWhile
* take
* takeWhile
* takeRight
* takeRightWhile

**Objects**

* functions
* mapKeys
* findKey
* omit
* clone
* tap
* has
* set
* matcher
* property
* propertyOf
* isMatch
* isEmpty

**Functions**

* bindAll
* delay
* defer
* once
* after
* before
* restArgs
* spread
* arity (`ary` from lodash)
* curry
* curryRight
* flow (could use better names for these, perhaps...)
* flowRight
* wrap
* negate

**Utility**

* identity
* constant
* noop
* random
* uniqueId
* result
* now
* gt
* gte
* lt
* lte

**String**

* camelCase
* capitalize
* delatinize (`deburr` from lodash)
* dasherize (`kebabCase` from lodash)
* underscore (`snakeCase` form lodash)
* headline (Let's try to do a real solid "Headline Case" implementation. It's worth it.)
* truncate (`trunc` from lodash)
* words
* startsWith
* endsWith
* escapeRegExp
* pad
* padLeft
* padRight
* trim
* trimLeft
* trimRight
* parseInt

**HTML**

* escape
* unescape
* template

**Math**

* max
* min
* add
* sum
* inRange

**Types**

* isElement
* isArray
* isTypedArray
* isObject
* isArguments
* isError
* isFunction
* isString
* isNumber
* isFinite
* isBoolean
* isDate
* isRegExp
* isNaN
* isNull
* isUndefined

**Deep**

* isEqual
* flattenDeep
* cloneDeep

