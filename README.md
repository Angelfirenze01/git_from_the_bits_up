I created this file while working through Tim Berglund seminar on Git.

It is covering things I have yet to learn, such as hash-object, cat-file -p, -t for the SHA-1 hash.

File --changes, Blob --file, Tree --file name, file mode, directory.  Git write-tree.  Git Porcelain commands.  Different far-back-end commands for collaborative workflows.  What is the Git (?/?/?/?/?) <i>--missing-ok?</i> command and what does it do?

Quitting git log from a bash script, citation <a href="https://stackoverflow.com/questions/12677002/quitting-git-log-from-a-bash-script" target="_blank">StackOverflow</a> by <a href="https://stackoverflow.com/users/984284/xero" target="_blank"></a>.

<i>git --no-pager log --graph -10 --all --color --date=short --pretty=format:"%Cred%x09%h %Creset%ad%Cblue%d %Creset %s %C(bold)(%an)%Creset"</i>

I'd forgotten about the 'reflog' command, which creates a list of the changes made to my commits.