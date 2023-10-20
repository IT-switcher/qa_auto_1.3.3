# Я хочу добавить информацию про классные "Git tricks", зная которые, будет проще работать
## 1. Autocorrection
```js
git config --global help.autocorrect 1
  ``` 
## 2. Know your .git folder
```js
ls -a
 ``` 
## 3. View a file of another branch (without actually switching your branch)
Suppose you have a file called README.md, and it's in the main branch. You're working on a branch called dev
```js
git show main:README.md
 ``` 

