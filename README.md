# Objective

If [pivotaltracker.io](https://pivotaltracker.io) story 
id `#123456789` or 
link `https://www.pivotaltracker.com/story/show/123456789` is in the clipboard.

Insert markdown link 
```markdown
[#123456789](https://www.pivotaltracker.com/story/show/123456789)
``` 
to the git commit message.

If your don't want link in particular commit press `u` to undo.

As an alternative you can paste link manually with vim ex command `:P2Story`

# Installation

```vim
Plug 'a-b/pivotal-story-to-commit.vim'
```
