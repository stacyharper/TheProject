
I made mistakes on my Vim way. In my early days with my Text Eddie-tor, like lot of Vimer, I used plugins. LOT of plugins. Plugins are the dark side of the force. "Does the dark side be the stronger ? No, no, no. Quicker, easier, more seductive." Master Yoda to Luke Skywalker.
Plugins will give you unlimited power but, you'll lose some Vim advantages. You'll need your plugins to use Vim. You'll need NERDTreePlugin to surf your projects. You'll need Fugitive cause "It's faster than press Ctrl + Tab". Vim will become a monster thing that take 10 minutes to install all plugins with the Plug manager. Installing and compiling YouCompleteMe and FZF etc. It will take 3 second to swap buffers. Plugins incompatibility will throw errors.

Let me tell you one thing. 99% of what plugins do, Vim already do. Fast file exploration is native with netrw. Fast auto-completion is native with Omnicomplete. Spell checking is native. Why do you need NERDTree that just can't delete multiple files in same times ? Why do you need this stupid thing that make appear distractive letters all around the screen to jump to another point ?
Keep in mind the dark side is everywhere. Before installing plugins, re-think of what you really need.
My personal idea is to just install syntax based configuration. I override Html syntax to Html5 updates. I have build a twig template handler. I override Php Omnicomplete function to fit with new ctags norms. I have some little fixes to remove useless spaces or preserve screen position on buffer swap and some other things.

But the think is : I do not judge other Vimer that stick with plugins cause this is the Unix philosophy. Use different tools, the tools you need, the tools you choose, the tools that make you gain times. Use what works for you. If you stick with IDEs go for it. I just want to explain why I stick with Vim.