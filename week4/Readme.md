# Notes
This solved Apache not working on MacOS:
http://stackoverflow.com/questions/7381371/apache-wont-follow-symlinks-403-forbidden

The Reason is:
On the Mac OS (10.9.4) my ~/Documents had no execution rights and I had a git repo where it would host my site files. Granting chmod o+x on ~/Documents did the trick! Thanks! – Ernani Joppert Sep 13 '14 at 21:23

##Note - Seperated JS File and Symlink
Another important thing:
When separating JavaScript code from HTML Code, creating a new symlink is needed
