# TMUX COMMANDS

Just some notes for my tmux learning

### `<prefix>`
Default prefix: ctrl + b 

## Commands
### Creating a new window
`<prefix>` followed by `c` (followed by means I don't need to press `c` together with the prefix)

## Changing between windows
Way 1: `<prefix>` followed by `the window number at the bottom` (such as 0, 1, and so on depending on the number of windows that are open)

Way 2: `<prefix>` followed by `n` (next) or `p` (previous) 

## Killing the window
Way 1: `<prefix>` followed by `&`

Way 2:
```zshrc
tmux kill window
```

## Managing panes
### Splitting the windows horizontally
`<prefix>` followed by `%`

### Splitting the windows vertically
`<prefix>` followed by `"`

### Navigating between the panes
`<prefix>` followed by either the `↑` arrow or the `←` arrow or something similar

Panes also have numbers; we can use this to navigate around them as well:

`<prefix>` followed by `q`, and then followed by `the pane number that was displayed`

### Swapping the panes around inside the window
`<prefix>` followed by `{` or `}`

#####


#####
