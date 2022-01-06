# tmux
## Installation in debian
   Due to it's popularity `tmux` is availbale on most debian or you can install as follows
    
     sudo apt-get update && sudo apt-get install tmux
    
All tmux command starts with `ctl+b` When you press it in a tmux session, it alerts tmux to "listen" for the next key or key combination that follows.
### creating new window
* To create new tmux window just place `ctrl+b` to let tmux listen and press `c` .so here `c` is command to create new windows in tmux
   
### Splitting windows into panes

Once you have created more than one window in tmux, it's often useful to see them all in one window. You can split a window horizontally (meaning the split is horizontal, placing one window in a North position and another in a South position) or vertically (with windows located in West and East positions).

   *  To create a horizontal split, press `ctrl+b` followed by `"` (that's a double-quote).
   *  To create a vertical split, press `ctrl+b` followed by `%` (percent).
