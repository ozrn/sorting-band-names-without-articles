# JS30# 17: sorting-band-names-without-articles
This is yet another coding challenge from JS30 series by Wes Bos.<br><br>
This exercise sorts the band names without "the", "a" or "an" in front of the actual band name by using regular expression, replace and sort methods.
### The sort method()
It sorts the elements of an array and that means it returns to an array with the items sorted. Here, in this step, it is created an array
by sorting the band names alphabetically.

```const sortedBands = bands.sort((a, b) => a > b ? 1 : -1); ```
### The replace method()
It is is used on strings in JavaScript to replace parts of string with characters. The replace method accepts two arguments: the string to be replaced (pattern), and what the string would be replaced with (replacement). The pattern can be a string or a regular expression.

```const strip = (bandName) => bandName.replace(/^(a |the |an )/i, "").trim(); ```
