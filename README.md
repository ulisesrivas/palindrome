# palindrome
A palindrome detector for use with Learn Enough JavaScript to Be Dangerous

This is a sample NPM module created in Learn Enough JavaScript to Be Dangerous by Michael Hartl.

The module can be used as follows:

$ npm install --global mhartl-palindrome
$ vim test.js
let Phrase = require("ulises-rivas-palindrome");
let napoleonsLament = new Phrase("Able was I, ere I saw Elba.");
console.log(napoleonsLament.palindrome());
$ node test.js
true
