To create and remove 20 directories and to make a single path of 10 directories and remove them all, this is what I did: <br>

<blockquote> 
Rajs-MacBook-Air:chapter_7 raj$ mkdir -p 1/2/3/4/5/6/7/8/9/10/11/12/13/14/15/16/17/18/19/20 <br>
Rajs-MacBook-Air:chapter_7 raj$ ls <br>
1		README.md	temp <br>
Rajs-MacBook-Air:chapter_7 raj$ cd 1 <br>
Rajs-MacBook-Air:1 raj$ cd 2 <br>
Rajs-MacBook-Air:2 raj$ cd 3 <br>
Rajs-MacBook-Air:3 raj$ cd 4 <br>
Rajs-MacBook-Air:4 raj$ cd 5 <br>
Rajs-MacBook-Air:5 raj$ cd 6 <br>
Rajs-MacBook-Air:6 raj$ cd 7 <br>
Rajs-MacBook-Air:7 raj$ cd 8 <br>
Rajs-MacBook-Air:8 raj$ cd 9 <br>
Rajs-MacBook-Air:9 raj$ cd 10 <br>
Rajs-MacBook-Air:10 raj$ cd 11 <br>
Rajs-MacBook-Air:11 raj$ cd 12 <br>
Rajs-MacBook-Air:12 raj$ cd 13 <br>
Rajs-MacBook-Air:13 raj$ cd 14 <br>
Rajs-MacBook-Air:14 raj$ cd 15 <br>
Rajs-MacBook-Air:15 raj$ cd 16 <br>
Rajs-MacBook-Air:16 raj$ cd 17 <br>
Rajs-MacBook-Air:17 raj$ cd 18 <br>
Rajs-MacBook-Air:18 raj$ cd 19 <br>
Rajs-MacBook-Air:19 raj$ cd 20 <br>
Rajs-MacBook-Air:20 raj$ cd .. <br>
Rajs-MacBook-Air:19 raj$ rmdir 20 <br> 
Rajs-MacBook-Air:19 raj$ ls <br>
Rajs-MacBook-Air:19 raj$ cd .. <br>
Rajs-MacBook-Air:18 raj$ rmdir 19 <br>
Rajs-MacBook-Air:18 raj$ cd .. <br>
Rajs-MacBook-Air:17 raj$ rmdir 18 <br>
Rajs-MacBook-Air:17 raj$ cd .. <br>
Rajs-MacBook-Air:16 raj$ rmdir 17 <br>
Rajs-MacBook-Air:16 raj$ ls <br>
Rajs-MacBook-Air:16 raj$ cd .. <br>
Rajs-MacBook-Air:15 raj$ rmdir 16 <br>
Rajs-MacBook-Air:15 raj$ cd .. <br>
Rajs-MacBook-Air:14 raj$ rmdir 15 <br>
Rajs-MacBook-Air:14 raj$ cd .. <br>
Rajs-MacBook-Air:13 raj$ rmdir 14 <br>
Rajs-MacBook-Air:13 raj$ cd .. <br>
Rajs-MacBook-Air:12 raj$ rmdir 13 <br>
Rajs-MacBook-Air:12 raj$ cd .. <br>
Rajs-MacBook-Air:11 raj$ rmdir 12 <br>
Rajs-MacBook-Air:11 raj$ cd .. <br>
Rajs-MacBook-Air:10 raj$ rmdir 11 <br>
Rajs-MacBook-Air:10 raj$ cd .. <br>
Rajs-MacBook-Air:9 raj$ rmdir 10 <br>
Rajs-MacBook-Air:9 raj$ cd .. <br>
Rajs-MacBook-Air:8 raj$ rmdir 9 <br>
Rajs-MacBook-Air:8 raj$ cd .. <br>
Rajs-MacBook-Air:7 raj$ rmdir 8 <br>
Rajs-MacBook-Air:7 raj$ cd .. <br>
Rajs-MacBook-Air:6 raj$ rmdir 7 <br>
Rajs-MacBook-Air:6 raj$ cd .. <br>
Rajs-MacBook-Air:5 raj$ rmdir 6 <br>
Rajs-MacBook-Air:5 raj$ cd .. <br>
Rajs-MacBook-Air:4 raj$ rmdir 5 <br>
Rajs-MacBook-Air:4 raj$ cd .. <br>
Rajs-MacBook-Air:3 raj$ rmdir 4 <br>
Rajs-MacBook-Air:3 raj$ cd .. <br>
Rajs-MacBook-Air:2 raj$ rmdir 3 <br>
Rajs-MacBook-Air:2 raj$ cd .. <br>
Rajs-MacBook-Air:1 raj$ rmdir 2 <br>
Rajs-MacBook-Air:1 raj$ cd .. <br>
Rajs-MacBook-Air:chapter_7 raj$ rm dir 1 <br>
Rajs-MacBook-Air:chapter_7 raj$ ls <br>
README.md	temp <br>
</blockquote>

Can you remove the tmp directory?
> rmdir temp

Let's clear out your log directory.
> rmdir log

