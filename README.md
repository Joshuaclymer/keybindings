## Jawsh's vscode keybindings

### Setup
- install vim for vs code.
- install CodeGPT for vs code (id DanielSanMedium.dscodegpt). Set the model to gpt-4 in settings.
- install Github Copilot and pay for a subscription (it's worth it).
- 'keybindings.json.' Replace the contents of your vscode keybindings.json file with the one in this repo.

### Usage

**Text editing**
- `tab` escapes insert mode in VIM (not `esc`). `tab` is much easier to reach. If you need to indent use `>` in vim normal mode.

**Jupyter notebooks**
- You can use normal vim shortcuts to navigate jupyter notebooks. Hit `tab` once to escape INSERT mode and once again to navigate blocks. You can create, copy, delete, etc blocks like you would text.
- `ctrl+enter` runs a block.
- `shift+enter` runs a block and moves to the next block.
- `option+shift+enter` restarts the kernel and runs all blocks up to the current block.
- `ctrl+r` restarts the kernel.
- `ctrl+option+x` clears all the outputs (good for reducing clutter). I recommend frequently clearing outputs.

**Editor Navigation**
- `ctrl+j` switches to the tab on the left. `ctrl+k` switches to the tab on the right.
- `ctrl+x` closes the current tab. I recommend closing tabs by default to avoid clutter.
- `ctrl+t` opens and focuses the terminal. Hit `ctrl+t` again to move the cursor back to the editor.
- `ctrl+p` opens the file search bar. use `ctrl j` and `ctrl k` to navigate the search options.
- `ctrl+e` opens the file explorer and focuses the current file. Use `ctrl+b` to close the file explorer. I recommend keeping it closed in general to reduce cognitive load. Hit `ctrl+e` again to focus the editor again without closing the file explorer.
- `cmd+o` opens a new folder or file in vscode that can be outside the current working directory.

**Copilot**
- `ctrl+space` accepts suggestions.

**CodeGPT**
- Visually select code and then hit `ctrl+\`. Then type a question about the code you selected. Use `ctrl+\` again to close the chat.
- You can also open the chat normally by using `ctrl+\` 

**File Explorer Navigation**
- `/` opens search. Cancel with `tab`.
- Use the standard `hjkl` keys to navigate the file tree. Use `ctrl+h` to go to parent without collapsing it (I like to collapse by defualt to keep it clean)
- Use `l` or `enter` to open a file.
- Use `ctrl+c`, `ctrl+x`, `ctrl+v`, `ctrl+d` to copy, cut, paste, and delete files respectively.
- Use `ctrl+r` to rename a file or folder.
- Use `ctrl+n` to create a new file and `ctrl+f` to create a new folder.

**Terminal**
- `ctrl+t` toggles focus to terminal.
- `option+h` toggles terminal visibility.
- `option+f` toggles terminal full screen mode.
- `ctrl+shift+j` and `ctrl+shift+k` switch between terminals
- `ctrl+shift+t` opens a new terminal.
- `ctrl+x` closes the current terminal.
- I recommend using vim keybindings in the terminal (to edit commands). You can do this by adding `set -o vi` to your `~/.bashrc` file.

**Debugging**
- `option+c` starts a debug session and steps over breakpoints.
- `opton+r` restarts the debug session.
- `option+b` toggles breakpoint on current line.
- `option+s` shows variable value under the cursor.
