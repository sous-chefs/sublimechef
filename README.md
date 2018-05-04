# SublimeChef

A Sublime Text Package for authoring Chef related files.

This Package provides several code snippets designed to make writing chef recipes faster and even more fun. Each snippet has sensible defaults, carefully chosen placeholders, and several variations to cover almost all of your recipe needs.

Maybe this is better explained with a [youtube demo video](http://www.youtube.com/watch?v=4VtDj_ar1Xg).

## Install

If you have Package Control installed in Sublime Text just press ctrl+shift+p (Windows, Linux) or cmd+shift+p (OS X) to open the Command Palette. Start typing 'install' to select 'Package Control: Install Package', then search for Chef and select it. That's it.

You can also install this package manually by entering the Packages directory of Sublime Text and issuing on a terminal:

```
git clone https://github.com/sous-chefs/SublimeChef Chef
```

## Completions

These are the available completions:

```
actionn
bash_script
cookbook_file
cookbook_filef
cron
cronf
csh_script
deploy
directory
directoryf
directoryr
env
erl_call
execute
executef
executen
file
filec
filef
git
group
groupa
http_request
http_requestp
ignoref
include_recipe
ksh_script
link
linkf
linkh
log
logd
mdadm
metadata
metadataf
mount
mountf
mountl
mountn
not_if
not_ifd
notifies
notifiesi
ohai
ohaip
only_if
only_ifd
package
packageo
packager
packagev
perl_script
python_script
remote_directory
remote_directoryf
remote_file
remote_filef
remote_filem
retries
role
ruby_script
ruby_block
script
service
servicep
subscribes
subscribesi
subversion
supports
template
templatev
user
```
