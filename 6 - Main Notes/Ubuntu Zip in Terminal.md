To zip a folder or file using the terminal on Ubuntu (or any Linux distribution that uses `zip`), you can use the `zip` command. Here's how you can do it:

### Zip a Single File

If you want to zip a single file, use the following syntax:

```bash
zip compressed.zip filename
```

Replace `compressed.zip` with the desired name for your zip file and `filename` with the name of the file you want to zip.

For example, to zip a file named `example.txt` into `example.zip`, you would run:

```bash
zip example.zip example.txt
```

### Zip a Folder and its Contents

If you want to zip an entire folder and all its contents recursively, use the `-r` option (recursive):

```bash
zip -r compressed.zip foldername
```

Replace `compressed.zip` with the desired name for your zip file and `foldername` with the name of the folder you want to zip.

For example, to zip a folder named `documents` into `documents.zip`, you would run:

```bash
zip -r documents.zip documents
```

### Adding Multiple Files and Folders

You can also zip multiple files and folders into a single zip file by listing them after the zip file name:

```bash
zip compressed.zip file1.txt file2.txt folder1 folder2
```

### Additional Options

- **Exclude Files:** You can exclude specific files or directories using the `-x` option followed by a pattern or filename. For example, to exclude all `.log` files, you can use `-x "*.log"`.

- **Compression Level:** By default, `zip` compresses files with normal compression. You can specify different compression levels using the `-1` (fastest) to `-9` (best compression) options.

### Example with Compression Level:

```bash
zip -9 -r compressed.zip foldername
```

This command compresses the folder `foldername` into `compressed.zip` using the highest compression level (`-9`).

### Extracting Zip Files

To extract a zip file, you can use the `unzip` command:

```bash
unzip compressed.zip
```

This command will extract the contents of `compressed.zip` into the current directory.

Using these commands, you can efficiently zip and unzip files and folders from the terminal on Ubuntu or any Linux distribution that supports

the `zip` utility. It's a straightforward way to manage file compression and archival directly from the command line.