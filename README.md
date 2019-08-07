**NOT PUBLISHED YET / WORK IN PROGRESS**


# Elm Syntax Highlighting

Just add syntax highlighting for Elm.

For people who like simple editors.


## Install Instructions

- [Mac](install/mac.md)
- [Linux](install/linux.md)
- [Windows](install/windows.md)


## Recommended Workflow

I do all of my Elm development with Terminal and Sublime Text open next to each other like this:

![Recommended Workflow](install/images/workflow.png)

I mostly focus on the code in Sublime Text.

When I am curious if things work, I switch to Terminal and run something like `elm make src/Main.elm` to see if I get any errors.

Then I switch back to Sublime Text and use **Ctrl-t** (or **Cmd-t** on Mac) to navigate to the relevant files and make any fixes.


## Workflow Benefits

The recommended workflow has some underappreciated benefits:

1. **Fast** - Never wait for a slow editor. No background tasks eating RAM and CPU.
2. **Flexibile** - Some projects needs more than an `elm make` call. I can switch to `elm reactor` or a custom `./build.sh` script and keep essentially the same workflow.
3. **Robust** - Not much can go wrong here, so I never spend time messing with integrations. Changes in `elm`, `elm-test`, or `elm-format` are only a concern in the terminal.

I really love this balance! It has that particular character of focused designs.

* * *

That said, I know some people want a bit more, so I made [`elm-format-on-save`](https://github.com/evancz/elm-format-on-save) as well. It may be worth setting this up once you have been happily using Elm for a while and become curious what it might be like to use Elm at work.
