# Underdash.js

This is an experimental and provisional Underscore+Lodash merge repo. Nothing
to see here, apart from sketches and wild ideas for the moment.

**Fleshing out a consensus API:**

## "Core" Functions

**Iteration**

* each (forEach)
* map
* mapObject (mapValues)
* reduce
* filter
* find
* reject
* any (some)
* all (every)
* contains (includes)
* invoke

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
* allKeys (keysIn)
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
* has
* matcher (match)
* isMatch
* property
* propertyOf

**Functions**

* bind
* partial
* memoize
* throttle
* debounce
* compose (backflow, flowRight)

**Utility**

* noConflict
* underdash (`runInContext` from lodash)
* times
* mixin
* iteratee
* chain
* value
* attempt

## "More" Functions

**Iteration**

* transform
* reduceRight
* at
* sortBy
* sortByAll
* sortByOrder
* shuffle
* sample
* toArray
* toPlainObject
* size
* partition
* where
* findWhere
* pluck

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
* get
* set
* tap
* isEmpty

**Functions**

* bindAll
* delay
* defer
* once
* after
* before
* restArgs (restParam)
* spread
* arity (ary)
* curry
* curryRight
* flow
* flowRight (compose)
* wrap
* negate

**Utility**

* constant
* identity
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
* round
* floor
* ceil

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
