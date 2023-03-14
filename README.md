<h1 align="center">Top 11 Git Commands That Every Developer Should Know 🐱‍👤</h1>

[//]: # (Table of Content)

<a name="top"></a>

## Top 11 Git Commands That Every Developer Should Know 🙋‍♂️ content

> Click on any topic to go there

- [git config](#git-1)
- [git init](#git-2)
- [git clone](#git-3)
- [git add](#git-4)
- [git commit](#git-5)
- [git push](#git-6)
- [git pull](#git-7)
- [git merge](#git-8)
- [git checkout](#git-9)
- [git log](#git-10)
- [git branch](#git-11)


***


<a name="git-1"></a>
### 1. git config 

**`git config` is a command that allows you to configure Git on your system. It enables you to view and modify Git's settings, such as your user name and email address, default text editor, and more.**

**The `git config` command is used to set configuration values that affect the behavior of Git. Configuration values can be set globally or locally, depending on whether you want the configuration to apply to all Git repositories on your system or just the current repository.**

**Some common use cases of the `git config` command includes setting your user name and email address, configuring the default text editor, and customizing Git's behavior.**

**By using `git config` , you can tailor Git to your specific needs and preferences, making it easier and more efficient to work with Git on your projects.**

#### Setting your user name and email address globally:

```Bash
git config --global user.name "jakaria455173"
git config --global user.email "jakaria455173@gmail.com"
```

#### You can read back these values as: 

```Bash
git config --list
```

#### Output

``````Bash
user.name=jakaria455173
user.email=jakaria455173@gmail.com
``````

### When you open the global configuration file `~/.gitconfig`, you will see the content saved as:

```Bash
[user]
    name = jakaria455173
    email = jakaria455173@gmail.com
```

#### [Go to top:arrow_up: ](#top)

<a name="git-2"></a>
















