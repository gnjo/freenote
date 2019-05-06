# freenote
all resizable gird editor

# files
```
//common function
https://gnjo.github.io/use.js

index.html
index.pack.js
index.pack.css

freenote.html
freenote.pack.js
freenote.pack.css
```
# system
- ```index.html```: search and create gistid. to href ```freenote.html?id=xxxxx```
- if not id, then localStorage save. ```freenote.html```

# type
```
type is first line search.
＃基本エディタ : type==='＃'
＊コメント : type==='＊'
＠https://...png : type==='＠'
other : type==='...' //default is 1.6rem head, like a h1. just center.
```
