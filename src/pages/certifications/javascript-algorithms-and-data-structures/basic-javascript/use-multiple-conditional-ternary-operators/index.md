---
title: Use Multiple Conditional (Ternary) Operators
---
## Use Multiple Conditional (Ternary) Operators

This is a stub. <a href='https://github.com/freecodecamp/guides/tree/master/src/pages/certifications/javascript-algorithms-and-data-structures/basic-javascript/use-multiple-conditional-ternary-operators/index.md' target='_blank' rel='nofollow'>Help our community expand it</a>.

<a href='https://github.com/freecodecamp/guides/blob/master/README.md' target='_blank' rel='nofollow'>This quick style guide will help ensure your pull request gets accepted</a>.

<!-- The article goes here, in GitHub-flavored Markdown. Feel free to add YouTube videos, images, and CodePen/JSBin embeds  -->
```javascript
  function checkSign(num) {
      return (Math.sign(num) === 1) ? "positive" : (Math.sign(num) === -1) ? "negative" : "zero"
  }
  
checkSign(10);
```
Using Multiple Conditional operators we check if given element is positive, negative or neutral and return the result.
