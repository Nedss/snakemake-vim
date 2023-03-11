This repo is a fork from official snakemake repo.   
I only keep vim config in order to have an easier import on lua-based neovim config.
---

A vim syntax highlighting definition for Snakemake.

To install via Vundle use:

    Plugin 'https://github.com/nedss/snakemake.git'}

To install via [vim-plug]( https://github.com/junegunn/vim-plug):

    Plug 'nedss/snakemake'

To manually install, copy `syntax/snakemake.vim` file to `$HOME/.vim/syntax`
directory and `ftdetect/snakemake.vim` file to `$HOME/.vim/ftdetect`.

Highlighting can be forced in a vim session with `:set syntax=snakemake`.

By default, all rules will be folded.  To unfold all levels, use `zR`.  `zM`
will refold all levels.  If you'd like to change the default, add
`set nofoldenable` to your `.vimrc`.  To learn more, see `:h fold`.
