relevant-article
---------------

## Compare

Compares keyword density of articles to attempt to determine how similar the articles are. The 100 most common English words are excluded. Values range from 0 (for not at all the same) to 1 (for the same).

```
var RelevantArticle = require('relevant-article');
console.log(RelevantArticle.compare(str1, str2));
```