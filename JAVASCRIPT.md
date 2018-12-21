# javascript tips

## print a large array to the console
 `console.log(JSON.stringify(largeArray))`

you can then re-direct the output to a file by adding this to the end of the command
` > file.txt`

NOTE - you might need to process the output, as it won't have any line breaks.


## find the max value in a array
this seems simple - `Math.max(...array)`, but might cause problems for big arrays (10^7)
(the same goes for `Math.min`)
it's discussed here [stackOverflow](https://stackoverflow.com/questions/1669190/find-the-min-max-element-of-an-array-in-javascript),
and there's an alternative solution using `reduce` that's apparently faster