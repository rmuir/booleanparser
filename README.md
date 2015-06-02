# booleanparser
The best boolean parser on the planet

All boolean parsers in java suck.
Boolean.parseBoolean() even proudly proclaims its shittiness in its docs:

    Example: Boolean.parseBoolean("True") returns true.
    Example: Boolean.parseBoolean("yes") returns false.
  
WTF!!!!

This parser exists so you can parse booleans correctly, without bugs in your program.
It will parse "true" to `true` and "false" to `false`. Anything else is an exception.
Finally, software you can rely upon.
