#### EMACS Commands  

#### Open emacs from termianl
- type: `emacs`

#### Command types
- C denotes `ctrl`
- M denotes `alt`
- RET denotes return or enter 
- Control -> `ctrl` key and Meta is `alt` key

#### Open ./emacs file
- `C-x C-f` and type ~/.emacs

Control Cmds  | Description                                       | Lisp function
------------- | ------------------------------------------------- | --------------------
C-x C-+       | inc font size                                     |
C-x C--       | dec font size                                     |
C-x C-s       | saves a file                                      |
C-x C-f       | find a file                                       |
C-x d         | open a dir                                        |
C-h b         | returns all commands                              |
C-x 0         | close a frame/window                              |
C-g           | cancels the current command if mistyped           |
C-x u         | undo                                              |
C-x C-c       | quit emacs                                        |
C-h t         | to learn about emacs tutorial                     | 
C-x 2         | split the selected frame, one above the other     | (split-window-below)
C-x 3         | split the selected frame, positioned side by side | (split-window-right)

Meta Commands            | Description
------------------------ | -------------
M-x customize-theme      | change the editor theme
M-x list-packages        | returns all packages 
M-x package-install      | install a package 
M-x term or M-x shell or M-x ansi-term   | opens a terminal

Commands for Lisp programming   | Description
------------------------------- | -------------
C-x C-e                         | place the cursorafter the closing parenthesis to see the result
