# How to Download a Raw File from GitHub

## Steps:

1. Navigate to the GitHub repository containing the file you want to download.

2. Locate and click on the file to open it.

3. Click the **"Raw"** button at the top-right of the file's content preview.

4. Save the file:
   - **Windows/Linux**: Right-click on the page and select **"Save As"**, or press `Ctrl + S`.
   - **Mac**: Right-click and select **"Save Page As"**, or press `Command + S`.
   
5. Choose a destination for the file, ensuring the file extension matches the original.

## Alternative Method (Direct URL):
- If you know the raw file URL, you can use the `wget` or `curl` command to download it directly:
  ```bash
  wget https://raw.githubusercontent.com/<username>/<repository>/<branch>/<file_path>
