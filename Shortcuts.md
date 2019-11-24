	# Intellij Notes

## Shortcuts
* `itar` - generates the following block of code (Loop)

`for (int i = 0; i < array.length; i++) {}`

* Reversing a string
 
`StringBuilder sb = new StringBuilder()`

`String reversedString = sb.reverse().toString();`


* `psvm` - generates the following block of code

```
public static void main(String[] args) {
}
```

* `Alt+Enter` - Takes a _suggestion_ to fix a syntax eror
* `Alt+Insert` - Generates code
* `Ctrl+Alt+l` - autoformats the code indentation


## How to create a new project
1. Click `File` from the menu bar at the top right
2. Select `New`
3. Select `Project`
4. Select `Maven`
5. Click `Next`
6. `GroupId` is basically your signature
	* `com.github.git-eddie` is a sensible signature
7. `ArtifactId` is basically the name of the project
	* `myproject` is a sensible signature
8. Click `Next`
9. Click `Finish`
10. Click `This Window` 

## How to capture a picture on your screen

1. Hit `Windows` type snip + open `Snipping Tool`

## GIT's Terminal

* Opening Terminal

 1. Go to GIT's directory
 2. Right click `git`
 3. Select `Git Bash Here`
 ---------------------------------------------
* **CREATING A REPOSITORY ON COMMAND LINE**

 1. git init
 2. git add 
 3. git commit -m "first commit"
 4. git remote add origin https://github.com/eddiem-git/testingexample.git
 5. git push -u origin master
 -------------------

* git config 

Usage `git config –global user.name “[name]” ` 

Usage `git config –global user.email “[email address]”  `

Sets the author name and email address to your commits.

------------------------------------------
* cd  `Change directory`
* cd ..   `Go back one directory`
* ls   `Gives a list`