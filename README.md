# templates
Templates for empty-files in different languages. Vim can be used to initialize a new file with these templates.

To use these templates, clone this repo to `~/.vim/templates`, then add lines like this to your `.vimrc`:

```
augroup skeletons
    :autocmd BufNewFile  *.R       0r ~/.vim/templates/sample.R
augroup END
```

Thanks to aregier for help with the vimrc setup!
