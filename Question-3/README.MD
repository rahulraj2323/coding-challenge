#  Online Challenge
## Solution for question-3

You pass in the object and a key to the function and get back the value.

## PREREQUISITES

- Python3.6 or higher

## Usage

Basic usage of this module is as follows:

```hcl
>>> from functools import reduce
>>> def get_value(object, keys, default=None):
...     return reduce(lambda d, key: d.get(key, default) if isinstance(d, dict) else default, keys.split("."), object)
...
>>> object={'a':{'b':{'c':'d'}}}
>>> key='a.b.c'
>>> get_value(object,key)

```

![alt text](https://github.com/rahulraj2323/kpmg_coding_challenge/blob/master/Question-3/Capture.PNG)
## Author
- [Rahul Raj](https://github.com/rahulraj2323)