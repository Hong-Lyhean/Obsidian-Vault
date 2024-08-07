To change the command `python3` to `python` in Ubuntu or reverse the change, you can use symbolic links. Here’s how you can do it:

### Changing `python3` to `python`

1. **Check current `python` version:**
   First, check which version of Python `python` points to by default (if any):
   ```bash
   python --version
   ```

2. **Create a symbolic link:**
   If `python` currently points to Python 2.x or doesn't exist, you can change it to Python 3 by creating a symbolic link:
   ```bash
   sudo ln -sf /usr/bin/python3 /usr/bin/python
   ```

   - `sudo`: Runs the command with superuser privileges.
   - `ln`: Command to create links.
   - `-sf`: Options for `ln` command:
     - `-s`: Creates a symbolic link.
     - `-f`: Forces the creation, overwriting existing `python` link if it exists.

3. **Verify the change:**
   Check again to verify that `python` now points to `python3`:
   ```bash
   python --version
   ```

### Reversing `python` to `python3`

If you need to revert back to the default behavior where `python` refers to Python 2.x (if Python 2.x is installed) or is unlinked:

1. **Remove the existing link:**
   ```bash
   sudo rm /usr/bin/python
   ```

   This removes the `python` symbolic link.

2. **Check if `python` is already linked to Python 2.x:**
   If you have Python 2.x installed and want `python` to point to it, check which version `python` currently points to (if any):
   ```bash
   python --version
   ```

   If it doesn't point to Python 2.x and you have it installed, you can create a link manually:
   ```bash
   sudo ln -s /usr/bin/python2.X /usr/bin/python
   ```
   Replace `2.X` with your specific Python 2 version (e.g., `python2.7`).

3. **Verify the change:**
   Check again to verify that `python` points to the correct version:
   ```bash
   python --version
   ```

### Important Notes:

- **Avoid altering system defaults:** Changing the default `python` executable can break system scripts and tools that rely on specific Python versions. It’s generally recommended to use `python3` explicitly for Python 3 scripts and `python2` for Python 2 scripts where necessary.
  
- **Virtual environments:** It's often better practice to use virtual environments (`venv`) for Python projects, where you can specify which Python version to use without changing system-wide settings.

By following these steps, you can effectively manage which version of Python `python` refers to on your Ubuntu system.