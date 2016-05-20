# Dan Learns Spacemacs

I'm documenting my learning process with Spacemacs. I'm including what I need to learn, what I'm stuck on, and what I've learned.


## Stuck

```
Nothing yet
```

## To Learn

* Find in file
* Go to line number
* Block editing
* Figure out what `helm` is
* How to set up a project folder and navigate quickly between files
  * Ignoring files listed in `.gitignore`


## Learned (common)

### Help

* `SPC ?`

(via [@bretthoerner](https://twitter.com/bretthoerner))

### How to Exit

`SPC q q`

(via [@igas](https://github.com/igas))

### How to Save

`SPC f s`

(via [@igas](https://github.com/igas))

### Open file

`spc f f`: opens up helm find files

### Change the font and font size

* Edit `~/.spacemacs`
  * Update `dotspacemacs-default-font` under `dotspacemacs/init`
  
(via [@SeanTAllen](https://twitter.com/SeanTAllen))

### Copy and paste from clipboard

Same as vim.

* `d`: Delete/cut
* `y`: Yank/copy
* `p`: Paste

### Visual select

* `v`: Start visual select
* `V`: Start visual select by lines
* `Ctrl+v`: Start visual select by block

## Learned (specialized)

### Make character upper/lowercase

Same as Vim.

* `~`: Toggle case under cursor
* Visual select
  * `U`: Uppercase
  * `u`: Lowercase

