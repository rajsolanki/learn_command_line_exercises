Rajs-MacBook-Air:chapter_10 raj$ touch foo.txt
Rajs-MacBook-Air:chapter_10 raj$ cp foo.txt temp/
Rajs-MacBook-Air:chapter_10 raj$ ls temp/
awesome.txt		newplace
foo.txt			something
iamcool.txt		thefourthfile.txt
neat.txt

I don't think this worked because I don't see the file in the new directory. Is this file hidden?

Rajs-MacBook-Air:~ raj$ cp .bash_profile ~/workspace/davinci_coders_t2_2014/learn_command_line_exercises/chapter_10

Robocopy is a command within Windows that copies with several features like the ability to be disrupted and continue copying once a connection is remade.

cp -r copies a dir and it's contents:

Rajs-MacBook-Air:chapter_10 raj$ cp -r temp/ temp2/
Rajs-MacBook-Air:chapter_10 raj$ ls
foo.txt	temp	temp2
Rajs-MacBook-Air:chapter_10 raj$ ls temp2/
awesome.txt		newplace
foo.txt			something
iamcool.txt		thefourthfile.txt
neat.txt

cp -r temp/ ~/Desktop

I noticed that it copied the contents of temp but not the directory itself.
