# Varaibles 

## Declaration 

var Name [type]
var Name [type] = value
Name := value 

## Visibility 

* lower case first letter for package scope
* upper case first letter to export 
* no private scope (but can be declared to a block) 


## Characteristics 

* can't redeclare, but can be shadowed 
* all variables MUST be used 

## Naming conventions 

* Pascal or camelCase 
* Capitalize acronyms 
* as short as reasonable 
* "longer names for longer lives" 

## Type conversions 

* destinationType(variable)
* use strconv package to convert to strings 

# Primitive types

* boolean


## Numeric types

###  Intreger 
* int8/16/32/64 ; uint8/16/32
* doesn't work between types
* bit operations ( &, |; ^, &^)
* bit shifting (<<, >>)

## Floating point numbers 
* (float32/64)
* no % in operatinos 
* no bit or bit shifting operations 