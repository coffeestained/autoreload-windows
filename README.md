# autoreload-windows
Autoreload - Windows 11 Support

Original: https://github.com/stevekrenzel/autoreload
Thank you!

Autoreload is a simple python script to watch a directory for changed files
and restarts a process when the change is detected. There were some issues with the original script on my windows machine. These changes resolved that.

To use autoreload:

1. Run `./autoreload <command to run and reload>`

For instance, I run `./autoreload python main.py`. This first runs
`python main.py`, then watches the current working directory and all
subdirectories for changes. If any changes are detected, then the
process is killed, and started all over again.
