# Longest Word Length Finder

## Description
This project contains a JavaScript function that finds the length of the longest word in a given sentence.

## Features
- Accepts a sentence as input.
- Splits the sentence into individual words.
- Finds the longest word.
- Returns the length of the longest word.

## Technologies Used
- JavaScript

## Function

```javascript
function findLongestWordLength(sentence) {
  const words = sentence.split(" ");
  let longest = 0;

  for (let i = 0; i < words.length; i++) {
    if (words[i].length > longest) {
      longest = words[i].length;
    }
  }

  return longest;
}
