<h1 align="center">Top Most Usefull Git Commands That Every Developer Should Know 🐱‍👤</h1>

[//]: # (Table of Content)

<a name="top"></a>

## Top Most Usefull Git Commands That Every Developer Should Know 🙋‍♂️ content

> Click on any topic to go there

- [git config](#git-config)
- [git version](#git-version)
- [git init](#git-init)
- [git status](#git-status)
- [git clone](#git-clone)
- [git add](#git-add)
- [git commit](#git-commit)
- [git push](#git-push)
- [git pull](#git-pull)
- [git merge](#git-merge)
- [git checkout](#git-checkout)
- [git log](#git-log)
- [git branch](#git-branch)


***


<a name="git-config"></a>
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

<a name="git-version"></a>


### 2. git version

**You can check your current version of Git by running the git --version command in a terminal (Linux, macOS) or command prompt (Windows). For example: git --version git version 2.7.4.**

<details>
	<summary> <b>গিট ভার্সন কমান্ড:</b> </summary>
	<p>গিট ভার্সন কমান্ড হলো git version। এই কমান্ডটি ব্যবহার করে আপনি আপনার সিস্টেমে ইনস্টল করা গিটের সংস্করণ নম্বর দেখতে পারবেন।

আপনি যদি আপনার টারমিনাল ওপেন করেন এবং git version টাইপ করেন তবে আপনার সিস্টেমে ইনস্টল করা গিটের সংস্করণ নম্বর দেখা যাবে। যেমনঃ

```
$ git version
git version 2.17.1
```
		
এখানে git version কমান্ডটি চালানোর পরে আউটপুট হিসেবে git version 2.17.1 দেখা যাচ্ছে, যেখানে 2.17.1 হলো আপনার ইনস্টল করা গিট সংস্করণ নম্বর।</p>
	
 </details>


#### Usage:

```
git version
```

#### [Go to top:arrow_up: ](#top)

<a name="git-init"></a>

### 3. git init

**The git init command creates a new Git repository. It can be used to convert an existing, unversioned project to a Git repository or initialize a new, empty repository. Most other Git commands are not available outside of an initialized repository, so this is usually the first command you'll run in a new project.**

<details>
	<summary><b>গিট ইনিট কমান্ড :</b></summary>
	<p>গিট ইনিট কমান্ড হলো গিট রিপোজিটরি তৈরি করার জন্য৷ এই কমান্ডটি দিয়ে আমরা কোন নির্দিষ্ট ফোল্ডার কে গিট রিপোজিটরি হিসেবে ব্যবহার করতে চাই তা নির্দিষ্ট করে দেই৷ এর ফলে ঐ ফোল্ডারে একটি .git নামক ফোল্ডার তৈরি হয় যেটি গোপন হয়ে থাকে এবং স্টেজ এবং কমিট করার জন্য সমস্ত লক্ষ্যযোগ্য ফাইল সংরক্ষণ করে রাখে৷</p>
 </details>


#### Usage :

```
git init
```

#### [Go to top:arrow_up: ](#top)

<a name="git-status"></a>

### git status

**The git status command `displays the state of the working directory and the staging area`. It lets you see which changes have been staged, which haven't, and which files aren't being tracked by Git.**

<details>
	<summary><b>git status কমান্ড</b></summary>
	<p>git status এটি একটি গিট কমান্ড যা আপনাকে আপনার গিট রেপোসিটরি স্থিতি সম্পর্কে বিবেচনা করতে সাহায্য করে। যখন আপনি এই কমান্ডটি রান করবেন, তখন আপনার কাছে একটি রিপোর্ট দেখা দেয়া হবে যা নিম্নরূপ হতে পারে:

- `Untracked files:` যে কোনও ফাইল যা আপনি আপনার রেপোসিটরিতে অ্যাড করা হয় নি, তা এখানে দেখানো হবে।
- `Changes not staged for commit:` আপনি কোনও পরিবর্তন করেছেন কিন্তু তা এখনো কমিট করা হয় নি।
- `Changes to be committed:` আপনি কোনও পরিবর্তন করেছেন এবং সেগুলি কমিট করা হবে।
- `Branch ahead of 'origin/master' by X commits:` আপনার মাস্টার শাখাটি গিটহাবের 'origin / master' ব্রাঞ্চের চেয়ে একটি বা একাধিক কমিট আগে রয়েছে।
- `Branch behind 'origin/master' by X commits:` আপনার মাস্টার শাখাটি `'origin / master'` ব্রাঞ্চের চেয়ে এক বা একাধিক কমিটটি পিছনে রয়েছে।

এই রিপোর্ট দেখে আপনি আপনার রেপোসিটরিতে কোনও সমস্যা আছে কিনা তা জানতে পারেন।</p>
 </details>

#### Usage:

```
git status
```








































