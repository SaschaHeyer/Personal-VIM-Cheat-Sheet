# Personal-VIM-Cheat-Sheet


## Shortcuts
* ciw - Delete word and switch to insert mode 
* y - yank
* p - paste
* v - visual selection 
* G - end of file
* g - begining of file
* A - move to the end of the line and switch to editing mode
* ci) - change inside parens (parens can be replace wich anything)
* a - append (write text after cursor)
* dw - delete word
* w - jump word wise forward
* b - jump word wise backward
* leader leader b - highlight and jump search backward
* leader leader w - highlight and jump search forward

## Visual Studio Code setup
```
defaults write com.microsoft.VSCode ApplePressAndHoldEnabled -bool false 
```

Settings
```
    "vim.smartRelativeLine": true,
    "vim.leader": "<space>",
    "vim.easymotion": true,
    "vim.insertModeKeyBindings": [
        {
          "before": ["j", "j"],
          "after": ["<Esc>"]
        }
      ],
```
