<h1 align="center">Top Most Usefull Git Commands That Every Developer Should Know 🐱‍👤</h1>

[//]: # (Table of Content)

<a name="top"></a>

## Top Most Usefull Git Commands That Every Developer Should Know 🙋‍♂️ Table Of Content

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

### 4. git status

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

#### [Go to top:arrow_up: ](#top)

<a name="git-clone"></a>

### 5. git clone

**git clone is primarily used to point to an existing repo and make a clone or copy of that repo at in a new directory, at another location. The original repository can be located on the local filesystem or on remote machine accessible supported protocols. The git clone command `copies an existing Git repository`.**

<details>
	<summary><b> git clone কমান্ড:</b></summary>
    গিট ক্লোন কমান্ড হল একটি গিট কমান্ড যা কোন রিপোজিটরির ক্লোন (অনুলিপি) তৈরি করায় ব্যবহার করা হয়। এটি স্থানীয় মেশিনের ডিরেক্টরি তে সরাসরি রিপোজিটরিকে ক্লোন করে নিয়ে আসে। এতে ক্লোন করার জন্য আবশ্যক পরিমাণ ইন্টারনেট সংযোগ এর জন্য ন্যূনতম ব্যবধান থাকে। এটি বিভিন্ন প্ল্যাটফর্মে ব্যবহৃত হয় যেমন উইন্ডোজ, ম্যাক ও লিনাক্স টার্মিনালে।

গিট ক্লোন করার জন্য সঠিক কমান্ডটি হল,

```
git clone <repository-url>
```
	
উদাহরণঃ

```
git clone https://github.com/example/repo.git
```
	
এখানে আমরা গিটহাব থেকে কোন একটি রিপোজিটরি ক্লোন করতে চাচ্ছি। তাই উল্লেখ্য যে আমরা সঠিক url টি ব্যবহার করছি নাকি।

কমান্ডটি চালানোর পরে গিট রিপোজিটরি ক্লোন হবে এবং লোকাল মেশিনে একটি নতুন রিপোজিটরি তৈরি হবে যা আপনি এর মধ্যে কাজ করতে পারবেন।
 </details>

#### Usage:

```
git clone
```
	
#### [Go to top:arrow_up: ](#top)

<a name="git-add"></a>

### 6. git add

<b>The git add command is used to add changes to the staging area in Git. When you make changes to a file in your local repository, those changes are not automatically tracked by Git. You need to explicitly tell Git which changes you want to include in the next commit. This is where the git add command comes in.

Here is the basic syntax of the git add command:

```
git add <file>
```
This command adds the specified file to the staging area. You can also use wildcards to add multiple files at once:

```
git add .
```
	
This command adds all changes in the current directory and its subdirectories to the staging area.

Once you've added your changes to the staging area, you can review them using the git status command. This will show you which files have been modified and which changes have been staged.</b>
	
	
<details>
	<summary><b>git add কমান্ড:</b></summary>
	
গিট এড কমান্ড হলো গিটে কোন ফাইল বা ফোল্ডার ট্র্যাক করার জন্য ব্যবহৃত হয়। এটি নতুন ফাইল বা ফোল্ডার ট্র্যাক করার জন্য ব্যবহৃত হলে গিট তাকে ট্র্যাক করবে এবং এটি স্টেজ এলাকায় যোগ করে দেবে। এটি একটি ফাইল বা ফোল্ডার ট্র্যাক করার জন্য ব্যবহৃত হলে গিট তাকে ট্র্যাক করবে এবং এটি স্টেজ এলাকায় যোগ করে দেবে।

উদাহরণঃ

```
git add file.txt
```
	
উপরের কমান্ড ব্যবহার করা হলো ফাইল নাম `file.txt` ট্র্যাক করার জন্য। এটি ফাইলটি স্টেজ এলাকায় যোগ করবে।
 </details>

#### [Go to top:arrow_up: ](#top)

<a name="git-commit"></a>

### 7. git commit
	
<b>The git commit command is used to save changes to a local repository after staging changes with git add. When you run git commit, Git will open your default text editor so you can enter a commit message describing the changes you made. The commit message should be a brief summary of what you changed and why you changed it.

The basic syntax for git commit is:

```
git commit -m "commit message"
```
	
This creates a new commit with the changes you've staged with git add and a commit message describing those changes. The -m flag allows you to specify the commit message directly on the command line, rather than opening a text editor.

You can also use the -a flag to automatically stage and commit all changes to tracked files in a single command:

```
git commit -a -m "commit message"
```
	
This is useful for quickly committing changes without having to stage them first. However, be careful with this command as it can accidentally commit changes that you didn't intend to include.</b>


<details>
	<summary><b>git commit কমান্ড:</b></summary>
গিট কমিট কমান্ড হল একটি গিট কমান্ড যা আপনাকে আপনার পরিবর্তনগুলি আপনার লোকাল রিপোজিটরিতে সংরক্ষণ করতে সাহায্য করে। এই কমান্ডটি আপনার পরিবর্তনগুলি স্থায়ীভাবে সংরক্ষণ করে এবং এটি আপনার লোকাল রিপোজিটরিতে একটি নতুন কমিট তৈরি করে।

গিট কমিট কমান্ড ব্যবহার করার জন্য আপনাকে প্রথমে আপনার কাজ শেষ করতে হবে এবং আপনার কাজ সম্পর্কিত কোন পরিবর্তন না থাকলে কমিট করার দরকার নেই।

গিট কমিট কমান্ড একটি ম্যাসেজ সহ হয় এবং এই ম্যাসেজ আপনার করা পরিবর্তনগুলি সম্পর্কে সংক্ষেপে বর্ণনা করে। এই ম্যাসেজটি আপনার পরিবর্তনগুলি সম্পর্কে সহজে বুঝতে সাহায্য করে এবং আপনার সমস্ত কমিট একটি নাম দেওয়া হয় যা আপনি পরবর্তীতে ব্যবহার করতে পারবেন।

একটি উদাহরণ দেওয়া হলো:

```
git commit -m "আমার পরিবর্তনগ
```
	
 </details>

#### [Go to top:arrow_up: ](#top)

<a name="git-push"></a>

### 8. git push
	
<b>The `git push` command is used to upload local repository content to a remote repository. This means that any changes you have made to your local repository will be reflected in the remote repository after the `git push` command is executed.

The basic syntax for `git push` command is:

```
git push <remote> <branch>
```

Here, `<remote>` refers to the name of the remote repository, and `<branch>` refers to the name of the branch in your local repository that you want to push to the remote repository.

For example, if you want to push the changes you have made in your local `master` branch to the `origin` remote repository, you would use the following command:

```
git push origin master
```

If the remote branch doesn't exist, `git push` will create it. If the remote branch does exist, `git push` will update it with the new changes.

It's worth noting that you may need to authenticate with the remote repository before you can push changes to it.</b>


<details>
	<summary>Table of Contents</summary>
গিট পুশ কমান্ড হল গিটের একটি কমান্ড যা লোকাল রিপোজিটরিতে কমিট করা পরিবর্তনগুলি রিমোট রিপোজিটরিতে পাঠানোর জন্য ব্যবহার করা হয়। এই কমান্ড ব্যবহার করে আপনি আপনার কাজের পরিবর্তনগুলি রিমোট রিপোজিটরিতে আপলোড করতে পারেন। 

যদি আপনি নতুন ফিচার বা কোড লাইন যুক্ত করে থাকেন তবে আপনাকে প্রথমে লোকাল রিপোজিটরিতে কমিট করতে হবে। এরপর আপনি গিট পুশ কমান্ড ব্যবহার করে আপনার কাজের পরিবর্তনগুলি রিমোট রিপোজিটরিতে আপলোড করতে পারেন। 

একটি উদাহরণ দেখা যাকঃ 

```
git push origin main
```

এখানে "origin" হল রিমোট রিপোজিটরির নাম এবং "main" হল মাস্টার ব্রাঞ্চের নাম। আপনি আপনার রিপোজিটরির নাম এবং ব্রাঞ্চের নাম দিয়ে কমান্ড ব্যবহার করতে পারেন। 

এই কমান্ডটি ব্যবহার করে আপনি আপনার কাজের পরিবর্তনগুলি রিমোট রিপোজিটরিতে আপলোড করতে পারবেন ।
 </details>


#### [Go to top:arrow_up: ](#top)

<a name="git-pull"></a>

	
### 9. git pull

<b>`git pull` is a command used in Git version control system to fetch and download content from a remote repository and immediately update the local repository to match that content. It is a combination of two other commands, `git fetch` and `git merge`. 

When you run `git pull`, Git will first fetch the latest changes from the remote repository and then merge those changes with the current branch in your local repository. If there are any conflicts between the remote changes and the local changes, Git will prompt you to resolve those conflicts before it completes the merge.

It's important to note that `git pull` can potentially overwrite changes you've made locally, so it's a good practice to commit any changes before running this command.</b>
	

<details>
	<summary><b>গিট পুল (git pull) কমান্ড:</b></summary>
গিট পুল (git pull) কমান্ড হলো গিট রিপোজিটরি থেকে কোড ফাইলগুলি আপডেট করার জন্য ব্যবহৃত কমান্ড। এটি স্থানীয় রিপোজিটরিতে কাজ করে এবং এটি রিমোট রিপোজিটরি থেকে পুশ করা এবং একই রিপোজিটরি থেকে পুল করা কোড ফাইলগুলি আপডেট করে। 

যখন আপনি কোনও প্রকল্পে কাজ করছেন এবং অন্য কেউ অবশ্যই আপনার পরিবর্তনগুলি আপলোড করেছেন তখন আপনার স্থানীয় রিপোজিটরিতে আপডেট করা প্রয়োজন হয়। এটি করতে আপনাকে নিম্নলিখিত কমান্ডটি চালাতে হবে:

```
git pull
```

এই কমান্ডটি রিমোট রিপোজিটরি থেকে সমস্ত পরিবর্তন ডাউনলোড করে আপনার স্থানীয় রিপোজিটরিতে আপডেট করে দেয়। যদি কোনও পরিবর্তন থাকে তবে এটি আপনার স্থানীয় কম্পিউটারে সেট করা হবে। আপনি একই রিপোজিটরি থেকে পুল এবং পুশ করতে পারবেন ।
 </details>

	
#### [Go to top:arrow_up: ](#top)

<a name="git-merge"></a>

### 10. git merge
	
<b>`git merge` is a Git command that allows you to combine changes from different branches into a single branch. When you merge a branch into another branch, Git integrates the changes made on the source branch into the target branch. 

Here's the basic syntax for the `git merge` command:

```
git merge <source-branch>
```

This command merges the changes from the `source-branch` into the currently checked out branch (i.e., the target branch). 

If there are any conflicts between the changes made on the source branch and the target branch, Git will prompt you to resolve them manually. Once you have resolved any conflicts, you can commit the changes to complete the merge.

It's worth noting that there are several strategies that Git can use to perform the merge, such as the "recursive" and "octopus" strategies. By default, Git uses the "recursive" strategy, which is suitable for most merge scenarios. However, you can specify a different strategy using the `--strategy` option.</b>


<details>
	<summary><b>git merge কমান্ড:</b></summary>
গিট মার্জ কমান্ড হলো গিটের একটি কমান্ড যা ব্যবহার করে আপনি একটি ব্রাঞ্চ থেকে অন্য একটি ব্রাঞ্চে পরিবর্তনগুলি সংযোজন করতে পারেন। যখন আপনি একটি ব্রাঞ্চে কাজ করছেন এবং আপনি অন্য একটি ব্রাঞ্চে কাজ করতে চান, তখন আপনি গিট মার্জ কমান্ড ব্যবহার করে দুটি ব্রাঞ্চ সমন্বয় করতে পারেন।

একটি উদাহরণ দিয়ে সহজে বোঝানো যাক। ধরুন আপনি দুটি ব্রাঞ্চ আছে যেখানে প্রথম ব্রাঞ্চ নামঃ "মাস্টার" এবং দ্বিতীয় ব্রাঞ্চ নামঃ "ফিচার"। আপনি ফিচার ব্রাঞ্চে কাজ করছিলেন এবং এখন আপনি মাস্টার ব্রাঞ্চে কাজ করতে চান। এই স্থিতিতে আপনি গিট মার্জ কমান্ড ব্যবহার করে দুটি ব্রাঞ্চ সমন্বয় করতে পারেন। নিচে কমান্ডটি দেখানো হলো:

```
git merge master (branch)
```

এখানে "মাস্টার" হলো আপনার মাস্টার ব্রাঞ্চের নাম এবং "ফিচার" হলো আপনার ফিচার ব্রাঞ্চ ।
 </details>

	
#### [Go to top:arrow_up: ](#top)

<a name="git-checkout"></a>

### 11. git checkout 
	
<b>`git checkout` is a Git command that allows you to switch between different branches or restore files in your working directory to a previous state. 

Here are some common use cases for `git checkout`:

- Switching between branches: `git checkout branch-name`
- Creating a new branch and switching to it: `git checkout -b new-branch-name`
- Discarding changes to a file: `git checkout -- file-name`
- Restoring a file to a specific commit: `git checkout commit-hash -- file-name`

It's important to note that `git checkout` can be a destructive command, as it can overwrite changes in your working directory. So, it's a good idea to commit any changes before running `git checkout`.</b>
	

<details>
	<summary>গিট চেকআউট (git checkout) কমান্ড:</summary>
গিট চেকআউট (git checkout) কমান্ড হলো গিট রিপোজিটরিতে বিভিন্ন ট্রি বা ব্রাঞ্চ এ Switched করার জন্য ব্যবহৃত হয়। এই কমান্ড দ্বারা আমরা গিট রিপোজিটরিতে কোন একটি ব্রাঞ্চ থেকে অন্য একটি ব্রাঞ্চে Switched করতে পারি বা একটি কমিট থেকে অন্য কমিটে Switched করতে পারি। 

যেমনঃ 

কমিট থেকে Switched করতে চাইলেঃ 

```
git checkout <commit-hash>
```

ব্রাঞ্চ থেকে Switched করতে চাইলেঃ 

```
git checkout <branch-name>
```

তবে এই কমান্ড ব্যবহার করার আগে আমাদের কোন কোন ফাইল মডিফাই করা হয়েছে তা স্টেজ করে রাখতে হবে না হলে ঐ ফাইল গুলো Switched করার সময় মুছে যাবে। 

 </details>


#### [Go to top:arrow_up: ](#top)

<a name="git-log"></a>

### git log

<b>`git log` is a command used in Git version control system to display the commit history of a repository. When you run `git log` in your terminal, it will show you a list of commits made in reverse chronological order, starting with the most recent commit.

By default, `git log` shows the following information for each commit:

- The commit hash, which is a unique identifier for that commit
- The author of the commit
- The date and time the commit was made
- The commit message, which describes the changes made in that commit

You can also use various options with the `git log` command to customize the output. For example, you can use the `--oneline` option to display each commit on a single line, or the `--graph` option to show the commit history as a graph.

Here's an example of running `git log` with the `--oneline` option:

```
$ git log --oneline
3a2c4b7 Add new feature
8c4f9d1 Fix bug in existing feature
e2a1b3f Initial commit
```

This will show the commit history with only the first few characters of the commit hash, along with the commit message, on a single line for each commit.</b>


<details>
	<summary>Table of Contents</summary>
  গিট লগ কমান্ড হল একটি গিট কমান্ড যা আপনাকে একটি রিপোজিটরির সমস্ত কমিট লগ দেখাবে। এটি আপনাকে কমিটের হ্যাশ, কমিটারের নাম, কমিটারের ইমেল, কমিটের তারিখ এবং কমিটের ম্যাসেজ দেখাবে।

আপনি নিচের কমান্ডটি ব্যবহার করে গিট লগ দেখতে পারেনঃ

```
git log
```

এই কমান্ডটি আপনাকে সমস্ত কমিট লগ দেখাবে। আপনি কমিট লগটি সংক্ষিপ্ত করতে পারেন এবং উপযুক্ত তথ্যগুলি দেখতে পারেন। উদাহরণস্বরূপ, আপনি আপনার কমিট লগটি তারিখ অনুযায়ী সংক্ষিপ্ত করতে পারেন এমনঃ

```
git log --since=2021-01-01 --until=2021-12-31
```

 </details>







