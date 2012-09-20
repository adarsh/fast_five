                                   Adarsh Pandit
                               adarsh@thoughtbot.com
                                     developer
                                     @adarshp

                      MMMMMMMMMMMMOZOOOOOOOOOOOOOMMMMMMMMMMMMM
                      MMMMMMMMMOZOOOOOOOOOOOOOOOOOZOMMMMMMMMMM
                      MMMMMMMZOOOOOOO$7$OOO$7$OOOOOOOZMMMMMMMM
                      MMMMMOOOOOOOOOOO++7Z7++OOOOOOOOOOOMMMMMM
                      MMMMOOOOOOOOOOOOZ..:..OOOOOOOOOOOOZMMMMM
                      MMMOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOMMMM
                      MMOOOOOOOOOOOOO.........OOOOOOOOOOOOOMMM
                      M8OOOOOOOOOOOOO.O...O...OOOOOOOOOOOOOOMM
                      MOOOOOOOOOOOOOO.       .OOOOOOOOOOOOOOMM
                      DOOOOOOOOOOOOOO.        OOOOOOOOOOOOOOMM
                      OOOOOOOOOOO.................OOOOOOOOOOZM
                      OOOOOOOOOOO.               .OOOOOOOOOOOM
                      OOOOOOOOOOO. ..         .. .OOOOOOOOOOOM
                      OOOOOOOOOOO. .,         $. .OOOOOOOOOOOM
                      DOOOOOOOOOO. .,         $. .OOOOOOOOOOMM
                      MOOOOOOOOOO. .,         $. .OOOOOOOOOOMM
                      MDOOOOOOOOOIO.,         $.O+OOOOOOOOOOMM
                      MMOOOOOOOOO,O.,   ..    $.O.OOOOOOOOOMMM
                      MMMOOOOOOOOOOO,   .O    $OOOOOOOOOOOMMMM
                      MMMMOOOOOOOOOO,   .O    $OOOOOOOOOZMMMMM
                      MMMMM8OOOOOOOZ.    O    .OOOOOOOOOMMMMMM
                      MMMMMMMOOOOOOOOOOOOOOOOOOOOOOOOZMMMMMMMM
                      MMMMMMMMMOOOOOOOOOOOOOOOOOOOOOMMMMMMMMMM
                      MMMMMMMMMMMMOOOOOOOOOOOOOOOMMMMMMMMMMMMM
                      MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM


Five Fast Vim Tips
==================

0) You will be faster in 2 weeks
- http://robots.thoughtbot.com/post/13164810557/the-vim-learning-curve-is-a-myth
- vimtutor (30 min)
- reduce distance from brain to cpu
- fingers on home keys (down with the mouse!)
- create "flow"

1) Move to a file fast
- :R(model | controller | view | migration | helper | observer...) <name>
- Create splits by appending S or V
- Go to File
- Uses Tim Pope's [rails.vim plugin](https://github.com/tpope/vim-rails)

2) Bounce around fast
- C-o to bounce back one jump
- / to find, n to keep finding
- :<linenumber> jumps there

3) Tmux/Turbux/Tslime for fast tests
- [Blog post](http://joshuadavey.com/2012/01/10/faster-tdd-feedback-with-tmux-tslime-vim-and-turbux/)

4) Move blocks fast with one command
- [Vim docs](http://vim.wikia.com/wiki/Moving_lines_up_or_down)

5) (fast) Change Comes From Within
- Change Inside Delimiters - type c-i-X where X is ", (, [, etc.
- Change 'Till X - type c-t-X where X is the query character
