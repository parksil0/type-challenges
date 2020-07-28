<!--info-header-start--><h1>Tail of Array <img src="https://img.shields.io/badge/-medium-eaa648" alt="medium"/> <img src="https://img.shields.io/badge/-%23array-999" alt="#array"/> <img src="https://img.shields.io/badge/-%234.0-999" alt="#4.0"/></h1><blockquote><p>by Anthony Fu <a href="https://github.com/antfu" target="_blank">@antfu</a></p></blockquote><p><a href="https://type-challenges.netlify.app/15/play" target="_blank"><img src="https://img.shields.io/badge/-Take%20the%20Challenge-3178c6?logo=typescript" alt="Take the Challenge"/></a> </p><!--info-header-end-->

> TypeScript 4.0 is Recommended in this challenge

Implement a generic `Tail<T>` that takes an Array `T` and returns it's last element's type.

For example

```
type arr1 = ['a', 'b', 'c']
type arr2 = [3, 2, 1]

type tail1 = Tail<arr1> // expected to be 'c'
type tail2 = Tail<arr2> // expected to be 1
```

<!--info-footer-start--><br><a href="../../README.md" target="_blank"><img src="https://img.shields.io/badge/-Back-grey" alt="Back"/></a> <a href="https://type-challenges.netlify.app/15/solutions" target="_blank"><img src="https://img.shields.io/badge/-Check%20out%20Solutions-de5a77?logo=awesome-lists&logoColor=white" alt="Check out Solutions"/></a> <a href="https://type-challenges.netlify.app/15/answer" target="_blank"><img src="https://img.shields.io/badge/-Share%20your%20Solutions-green" alt="Share your Solutions"/></a> <!--info-footer-end-->