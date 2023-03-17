<h1 align="center">Top Most Usefull Git Commands That Every Developer Should Know 🐱‍👤</h1>

[//]: # (Table of Content)

<a name="top"></a>

## Top Most Usefull Git Commands That Every Developer Should Know 🙋‍♂️ content

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

<details>
	<summary> <b>গিট কনফিগার করাঃ</b></summary>
    <p> গিট কনফিগ কমান্ড হলো একটি গিট কমান্ড যা আপনাকে আপনার সিস্টেমে আপনার নাম, ইমেল এবং অন্যান্য কনফিগারেশন সেটিংস সেট করতে সাহায্য করে। এই কমান্ডটি একটি ভ্যালু সেট করা জন্য ব্যবহার করা হয়। আপনি গিট কনফিগ কমান্ড ব্যবহার করে আপনার নাম এবং ইমেল ঠিকানা সেট করতে পারেন। প্রথমে, আপনার নাম সেট করতে পারেন। এটি একটি সিঙ্গেল কমান্ড হবে যা নিম্নলিখিত মত হবে: 


```
git config --global user.name "Your Name"
```

এবং তারপরে, আপনি আপনার ইমেল ঠিকানা সেট করতে পারেন। এটি একটি সিঙ্গেল কমান্ড হবে যা নিম্নলিখিত মত হবে: 

```
git config --global user.email "you@example.com"
```

এই অ্যার্গুমেন্টগুলি সেট করা হয় আপনার কম্পিউটার সিস্টেমে ব্যবহৃত হবে প্রতিবার যখন আপনি হোম ডিরেক্টরিতে git commit কমান্ড ব্যবহার করবেন। 

এই কমান্ডটি সাধারণত একবার একটি ব্যবহারকারী সেট করা হয়। আপনি সিস্টেমে একাধিক ব্যবহারকারী হলে, আপনার নাম এবং ইমেল সেটআপগুলি সাধারণত একটি যে কাজ করবে না। 

আপনি --global অপশনটি সেট করে সিস্টেমে একবার একটি কনফিগারেশন সেট করতে পারেন যা আপনার নিজের কম্পিউটারে ব্যবহার করা হবে সমস্ত গিট প্রকল্পের জন্য। 

এই কমান্ডটি আপনাকে উপযুক্ত কনফিগারেশন সেট করতে সাহায্য করবে যা আপনার গিট প্রকল্পে ব্যবহৃত হবে। </p>
    
 </details>


#### Setting your user name and email address globally:

```Bash
git config --global user.name "jakaria455173"
git config --global user.email "jakaria455173@gmail.com"
```

#### Setting your user name and email address locally:

```Bash
git config user.name "jakaria455173"
git config user.email "jakaria455173@gmail.com"
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

### 2. git init

> **The first command every developer should know is `git init`. This command initializes an empty Git repository in the current directory. This command creates a .git directory in the current directory, which is where Git stores all the information about the repository, including the commit history and the files themselves.
The git init command can be used in two ways:
Either changes a directory using the cd command and run git init to create a Git repository….**













































