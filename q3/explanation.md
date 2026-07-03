Explanation for Question 3
=========================

I created a regular file, a hard link, and a symbolic link to compare how Linux handles each type. The experiment showed that hard links share the same inode and survive when the original file is removed, while symbolic links depend on the target path remaining present.
