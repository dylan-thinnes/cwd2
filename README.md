Note: I wrote this program a long time ago. It works, but the code is ugly as
sin and poorly done in many places.

This is a command line utility for keeping a stack of directories that is
accessible across terminals, unlike the pushd/popd stack.

```
cwd <show | list | add | clear | rem | swap | pop>
```

- `show`: Shows the top of stack.
- `list`: Lists entire stack.
- `add`: Pushes current directory onto stack.
- `clear`: Clears entire stack.
- `rem`: Removes top of stack.
- `swap`: Swaps top and second-to-top on stack.
- `pop`: Removes top of stack, goes there.
