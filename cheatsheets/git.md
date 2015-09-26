# GIT

### Git clone a branch

[SO answer](http://stackoverflow.com/a/4568323/1913888)

`git clone -b my-branch https://git@github.com/username/myproject.git`

### Add an empty folder to Git

[SO answer](http://stackoverflow.com/a/5581995/1913888)

Put a single `.gitignore` file in the otherwise empty folder that you 
want to add to Git with:

```
*

!.gitignore
```