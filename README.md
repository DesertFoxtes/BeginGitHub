This is first repository 

# Summary

- [Basic writing and formatting syntax](#Basic-writing-and-formatting-syntax)
	- [Insert code](#a-Insert-code)
	- [Line Breaks](#b-Line-Breaks)
	- [Keyboard input](#d-Keyboard-input)
	- [Blockquote](#e-Blockquote)
	- [Link](#f-Link)
	- [Style text](#g-Style-text)
- [Process git](#Process-git)


## Basic writing and formatting syntax ##
**Description :** The section introduces the basic tags and syntax on [github.com](https//github.com) to create a description 

### a. Insert code 
**- Example :** Insert comment 
```
This section contains code or comments
```
If you insert code programming language :<br/>
**- Syntax :** <br/>
```
Some basic Git commands are:
``` Language
	git status
	git add
	git commit
```

**- Example :** Insert code > C programming language
```C
int main(){
    print('Hello words !');
}
```


### b. Line Breaks
**- Syntax :** \<br/> <br/>
**- Example :**

```
This is first line 
This is second line.
```

### d. Keyboard input
**- Syntax :** \<kbd>[Keyboard]\</kbd> <br/>
**- Example :**
<kbd>ALT + F4</kbd> 

### e. Blockquote
**- Syntax :** \> [quote] <br/>
**- Example :**
> Description : The section introduces the basic tags and syntax on github.com to create a description


### f. Link
**- Syntax :** \[Title link](link)
**- Example :** Go to : [google.com](https://google.com) 

### g. Style text
...#### Bold..
...**- Syntax :** \**[text]**  or \__[text]__<br/>..
...**- Example :** **This is bold text**..

...#### Italic..
...**- Syntax :** \*[text]* or \_[text]_ <br/>..
...**- Example :** *This text is italicized*..

### h. Highlighting
**- Syntax :** \`[title highlighting]\` <br/>
**- Example :** Inline `code` has `back-ticks around` it.


### i. Tab
**- Syntax :** \tab <br/>
**- Example :** 

This is a normal line of text<br/>
	This is the first level of bullet points, made up of <br/>
This is more indented, composed of <br/>
This is blockquoted text.
This is a second paragraph within the blockquoted text.

## Process git

- Commit :
```
	git add . 
	git commit -m "<msg commit>"
	// If push remote server 
	git push origin "branch or master"
```
- Branch :
```
 - Create branch :
	>git branch -b [branch name] 
 - Delete branch :
	>git branch -d [branch name]
```
- Merge  :
```
 - Merge branch1 to master
	>get meger [name branch]
```
- fetch and pull :
Diff : pull = get update remote server + meger != fetch  = get update remote server
```
 - Pull 
	>git pull [remote name] [remote branch]
 - Fetch 
	>git fetch [remote name] [remote branch]
 - Get branch Fetch 
	>git branch -a 
```

- stash
```
 - Save stash 
	> git add .
	> git stash # or git stash save
	> git stash list >"Show list stash saved"
	> git stash list -p > "Show content change"
	> git stash show "stash@{n}" > "Show detail content change"
	> git stash apply "stash@{n}" > "Revert state"
	> git stash pop 
	> git stash drop "stash@{n}" > "Remove in list stash"
	> git stash clear  > "Remove all stash"
```
- Revert
```	
	> git revert [commit-hash-code]
	> git reset --hard [commit-hash-code]
```
