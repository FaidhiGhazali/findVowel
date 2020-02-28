# findVowel

```
  function vowelIndices(word){
    word = word.toLowerCase();
    let vowelIndex = [];
    for (let i in word) {
      if ('aeiouy'.indexOf(word[i]) !== -1)
        vowelIndex.push(++i);
    }
    return vowelIndex;
  }

    console.log(vowelIndices('apple'));

```
