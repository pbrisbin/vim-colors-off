# vim-colors-off

*This is very much a work in progress*

For a number of weeks, I ran vim with `syntax off`. It was quite nice, 
with only two annoyances:

- Bright white on jet black was a bit off-putting.
- There were cases when I did miss the lack of color, vimdiff for 
  example.

Therefore, I aimed to find or create a colorscheme to solve these two 
issues.

The result is very much based on the [pencil][] colorscheme, which is 
surprising because it's a very colorful colorscheme, but:

- It uses a very sane approach to defining and setting colors
- It has nice background and foreground colors
- In the areas where I do want color, I like how it colors things

[pencil]: https://github.com/reedes/vim-colors-pencil

![Screenshot](shot.png)

Not super exciting...

## Installation

- Use [Vundle][]
- Add "pbrisbin/vim-colors-off" as a plugin

[vundle]: https://github.com/gmarik/Vundle.vim

## Usage

```
:colorscheme off
```

Supports both `background=light` and `background=dark`. I use dark, so 
that will always be the more tested.

