# The PHP Practitioner

Tutorial code from Laracasts.com "The PHP Practitioner" series: https://laracasts.com/series/php-for-beginners/

If you are new to PHP, this is good tutorial to follow.

## Project structure
When I was thinking about how to structure code of the series, the idea of each episode corresponding to lesson-n folder seemed very DRY-breaking.

The better solution is to match each lesson to specific commit and tag it with lesson-n.

That way it's easy to *git checkout lesson n* locally and jump between progressing state of the code in the series.
 
To follow best practices, keep things simple (and learn how to use git) we use three branches: *master*, *dev* and *hotfix*.

## Done and tested on the following environment:
- Windows 7 x64 bit;
- Laragon Lite 4.0 (Available for download: 
	- https://laragon.org/download/ & 
	- https://github.com/leokhoa/laragon/releases)

## List of lessons and tags:
| Lesson number | Name of the lesson | (Video duration + URL)|   *lesson_tag*|
|--|--|--|--|
1 |Step 1: Get PHP Installed|([3:51](https://laracasts.com/series/php-for-beginners/episodes/1)) |*tag*
2|Step 2: Install a Proper Code Editor|([9:21](https://laracasts.com/series/php-for-beginners/episodes/2))|*tag*
3|Step 3: Variables|([7:37](https://laracasts.com/series/php-for-beginners/episodes/3))|*tag*
4|Step 4: PHP and HTML|([12:38](https://laracasts.com/series/php-for-beginners/episodes/4))|*tag*
5|Step 5: Separate PHP Logic From Presentation|([3:46](https://laracasts.com/series/php-for-beginners/episodes/5))|*tag*
6|Step 6: Understanding Arrays|([7:44](https://laracasts.com/series/php-for-beginners/episodes/6))|*tag*
7|Step 7: Associative Arrays|([12:04](https://laracasts.com/series/php-for-beginners/episodes/7))|*tag*
8|Step 8: Booleans|([10:44](https://laracasts.com/series/php-for-beginners/episodes/8))|*tag*
9|Step 9: Conditionals|([6:58](https://laracasts.com/series/php-for-beginners/episodes/9))|*tag*
10|Step 10: Functions|([7:49](https://laracasts.com/series/php-for-beginners/episodes/10))|*tag*
11|MySQL 101|([16:18](https://laracasts.com/series/php-for-beginners/episodes/11))|*tag*
12|Classes 101|([16:10](https://laracasts.com/series/php-for-beginners/episodes/12))|*tag*
13|Intro to PDO|([15:16](https://laracasts.com/series/php-for-beginners/episodes/13))|*tag*
14|PDO Refactoring and Collaborators|([17:39](https://laracasts.com/series/php-for-beginners/episodes/14))|*tag*
15|Hide Your Secret Passwords|([6:27](https://laracasts.com/series/php-for-beginners/episodes/15))|*tag*
16|Make a Router|([24:19](https://laracasts.com/series/php-for-beginners/episodes/16))|*tag*
17|Dry Up Your Views|([7:02](https://laracasts.com/series/php-for-beginners/episodes/17))|*tag*
18|Array Filtering|([13:31](https://laracasts.com/series/php-for-beginners/episodes/18))|*tag*
19|Forms, Request Types, and Routing|([13:17](https://laracasts.com/series/php-for-beginners/episodes/19))|*tag*
20|Dynamic Inserts With PDO|([12:24](https://laracasts.com/series/php-for-beginners/episodes/20))|*tag*
21|Composer Autoloading|([4:38](https://laracasts.com/series/php-for-beginners/episodes/21))|*tag*
22|Your First DI Container|([7:04](https://laracasts.com/series/php-for-beginners/episodes/22))|*tag*
23|Refactoring to Controller Classes|([17:34](https://laracasts.com/series/php-for-beginners/episodes/23))|*tag*
24|Switch to Namespaces|([14:52](https://laracasts.com/series/php-for-beginners/episodes/24))|*tag*
25|Meet Your Batteries Included Framework: Laravel|([17:26](https://laracasts.com/series/php-for-beginners/episodes/25))|*tag*

## To do:

 - [x] Create this repository;
 - [x] Fill in basic license.md, readme.md. Squash commits;
 - [x] Understand and create project structure;
 - [ ] Watch series;
 	- Write code;
	- Make commits;
	- Make tags when merging lesson to master;
 - [ ] Update lesson table with tags;
 - [ ] Double check every merge to master and tagging;

## Thanks & stack

Best gratitude to git for being awesome tool!
Heads up to https://stackedit.io/ for awesome markdown editor;
JS playground: https://repl.it/
Easy to understand git model: https://nvie.com/posts/a-successful-git-branching-model/
For extracting lesson names, regex, you are the Lord, sir.