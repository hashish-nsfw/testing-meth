# testing-meth
This is a Linux terminal program that contains testing methodology and steps.

To run your script globally with the command `testing-meth`, follow these steps:

---

### 1. **Move the Script to a Directory in Your PATH**
Move your `testing.sh` script to a directory that is part of your system's `PATH`. For most systems, `/usr/local/bin` is a common choice for user-defined commands.

```bash
sudo mv testing.sh /usr/local/bin/testing-meth
```

### 2. **Make the Script Executable**
Ensure the script has execute permissions.

```bash
sudo chmod +x /usr/local/bin/testing-meth
```

---

### 3. **Verify Global Accessibility**
Test the script by running:

```bash
testing-meth
```

If the script runs as expected, it is now globally accessible.

---

### Notes:
- If `/usr/local/bin` is not in your `PATH`, you can check your `PATH` by running `echo $PATH`. Add `/usr/local/bin` to your `PATH` in your shell configuration file (`~/.bashrc`, `~/.zshrc`, etc.) if necessary.
- Avoid naming your script the same as an existing system command to prevent conflicts.

This setup will let you use `testing-meth` without needing to specify `./` or the full path.

