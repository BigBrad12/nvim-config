## This config is pretty much a copy of https://github.com/josean-dev/dev-environment-files

> Josean is a beast when it comes to NVIM. Feel free to watch his video on this config here https://www.youtube.com/watch?v=6pAG3BHurdM

> This config is slightly different with one or two plugins less I believe.

### PS, if you know of a way to remove the spelling diagnostics for comments, do please share :{}

### Keymaps:

> I have only noted the maps that I use often. If you are starting out in VIM, I advise first learning the basic VIM maps.

#### leader key = space / " "

- Insert mode
- - 'jk' = leave insert mode

- Normal mode (leader key is implied)
- - nh = Clear search highlights
- - '+' = Increment number (I've never used this before)
- - '-' = Decrement number (I've never used this before)

- Window management
- - sv = Create vertical split
- - sh = Create horizontal split
- - se = Make splits equal size
- - sx = Close currently focused split

- Tabs
- - to = Open
- - tx = Close
- - tn = Next
- - tp = Previos
- - tf = Open current buffer in new tab (basically just copy the tab)

- Searching files and strings in your project
- - ft = Find todos in project
- - ff = File files
- - fs = Find string in projects
- - fr = Find recent files
- - fc = Find string under your cursor
