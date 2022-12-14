# gh-get

(I won't be maintaining this.)

Gets any repository and branch from GitHub.

Syntax: `./gh-get -u [user] -r [repo] -b [branch]`
You can use `-h` for help.

If you're not in a GUI environment for any reason, you can run `curl -L -o gh-get.zip https://github.com/aarikpokras/gh-get/archive/refs/heads/main.zip`.

Then unzip the file. `unzip gh-get-main.zip`

Move the executable file out of the folder, into your home folder. `mv gh-get-main/gh-get ~/`

If it is not automatically given permission to execute, run `chmod 755 gh-get`.

Run it. `./gh-get -h`
