# smart_splitter.nvim
Smart splitter is a very simple plugin that allows you to simply call split, and let the nvim decide where to split.
Juggling between splitting horizontaly and vertically manually can be a hassle (not really), so Smart Splitter gets rid of that pain for you!

The plugin automatically figures out what is the current window with the most space available, then splits either horizontally or vertically based on the available space.

# Usage

In command mode you can call `:SmartSplit` and it will automatically create a new split wherever is most fitted in your current tabpage.

or in lua
```lua
require("smartsplit.smart-split").smart_split()
```

# Setup
**TODO**
