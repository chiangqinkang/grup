# grup

A rust-based grep CLI.

---

## Setup

### 1. Download the binary


### 2. Place the Binary in a Convenient Directory
Move the `grup.exe` file to a directory where you want it stored permanently, such as:
```
C:\Tools\grepp.exe
```

### 3. Add the Directory to PATH
To make `grup` accessible from any command prompt or terminal, you need to add its directory to your system's PATH:

1. **Locate Your PATH Variable**:
   - Press `Win + R`, type `sysdm.cpl`, and press Enter.
   - Go to the **Advanced** tab and click **Environment Variables**.

2. **Edit the PATH Variable**:
   - Under **System variables**, select `Path` and click **Edit**.
   - Click **New**, and enter the path to the directory where `grup.exe` is located (e.g., `C:\Tools`).
   - Click **OK** to save.

3. **Verify the PATH Update**:
   Open a new terminal and check if the command works:
   ```cmd
   grup --help
   ```


---

## Usage
Run the tool with the following command:

```bash
grup KEYWORD FILE_PATH
```
Currently, only support for one keyword is added. It should also be a valid unicode character
FILE_PATH should be p

---

## Quick Start

1. [Setup according to instructions above](#setup)
2. Download `poem.txt` included in the repository above, or simply copy and paste its contents into a file named `poem.txt`.
3. Ensure that you are in the same directory as `poem.txt` in the terminal.
4. Run `grup` on `poem.txt`. Put together, this command should look like `grup the poem.txt`. You should notice the following output:

   ```bash
   Then there's a pair of us - don't tell!
   To tell your name the livelong day
   ```
