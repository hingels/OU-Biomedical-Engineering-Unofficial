# How to use
1. To download a folder, install the Refined GitHub extension ([Chrome](https://chrome.google.com/webstore/detail/refined-github/hlepfoohegkhhmjieoechaddaejaokhf) or [Firefox](https://addons.mozilla.org/en-US/firefox/addon/refined-github-/?utm_source=addons.mozilla.org)) or paste the folder's URL into [DownGit](https://minhaskamal.github.io/DownGit).
   * If the folder's name starts with "!", download its parent folder instead!
   * If you installed Refined GitHub, first click on the folder in GitHub to open it. Then, click the three dots ("...") in the top-right corner and click "Download directory."
2. Unzip the folder you downloaded.
   * On Windows: right-click the .zip file, then click "Extract All."
   * On Mac: double-click the .zip file.
3. Move the folder to the place where you keep your code.
4. For CircuitJS files:
   1. Go to https://www.falstad.com/circuit/.
   2. Click "File," then "Open File…" to import the .circuitjs file.
5. For MATLAB code:
   1. In MATLAB, navigate to the folder in the "Current Folder" pane.
   2. Right-click the folder. (On a Macbook, this is a two-finger click.)
   3. Hover over "Add to Path," then click "Selected Folders and Subfolders."
6. For Python files:
   1. Open the Anaconda Navigator.
   2. Click the "Environments" tab.
   3. Click "Import" at the bottom of the screen.
   4. In the dialog, select the .yml or .yaml file in the folder you downloaded.
   5. Click "Import."
   6. Click on the new environment to activate it.
   7. Go back to the "Home" tab.
   8. For .py files:
      1. Under Spyder, click "Install" to install it in the new environment.
      2. Click "Launch" under Spyder.
      3. Click "File," then "Open…" to open the .py file.
   9. For .ipynb files:
      1. Under JupyterLab, click "Install" to install it in the new environment.
      2. Click "Launch" under JupyterLab.
      3. Navigate to the .ipynb file in JupyterLab's file browser to open it.
7. For code with explanations about a broad topic, open files **outside** the folders starting with "!." For code with explanations about specific functions, open files **inside** those "!" folders.

# Troubleshooting
* I'm getting the MATLAB error `'[insert function name here]' is not found in the current folder or on the MATLAB path`.
  * You'll need to repeat step #4 of the instructions above. MATLAB seems to frequently forget that we did this!
