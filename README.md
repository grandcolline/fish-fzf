fish-fzf
---

## install

```
$ brew install fasd
$ brew install fzf
$ fisher grandcolline/fish-fzf
```
## setting

For example...

fconfig.fish
```
function fish_user_key_bindings
	bind \cr '__fzf_history'
	bind \cb '__fzf_git_branch -a'
	bind \cl '__fzf_git_log'
	bind \cl\cl '__fzf_git_log -a'
	bind \cs '__fzf_git_status'
	bind \cd '__fzf_directory -f'
	bind \cd\cd '__fzf_directory'
	bind \cf '__fzf_file'
	bind \cf\cf '__fzf_file -g'
end
```

