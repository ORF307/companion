# Princeton ORF307 Optimization Companion

Supporting material for [Princeton ORF307 course: Optimization](https://stellato.io/teaching/orf307)

## 🚀 Run in GitHub Codespaces (JupyterLab in browser)

1. Click this badge to start a Codespace:

   [![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/orf307/companion)

2. GitHub will create a Codespace. By default, it opens in **VS Code in the browser**.
   - You can **ignore VS Code and close that tab** if you like.
   - To work in JupyterLab, go back to the GitHub repo page, open the green **<> Code** button → **Codespaces** tab, click the `…` menu next to your running (active) codespace, and choose **“Open in JupyterLab”**

   > If you prefer, you _can_ stay in VS Code and run notebooks there — both options work.

3. ⚠️ **Save your work locally**: Codespaces are temporary.
   - They stop after ~30 minutes of inactivity and may be auto-deleted after ~30 days.
   - Before you finish, download your files from JupyterLab:  
     Right-click a file → **Download**.

4. 📄 **Exporting to PDF**:
   - In JupyterLab, open your notebook, go to the top menu → **File → Save and Export Notebook As → PDF**.
   - This generates a PDF version of your notebook that you can download.

## Troubleshooting

- `Failed to process string with tex because latex could not be found` when generating plots.
  You most likely do not have latex installed (not present by default in colab). You can simply fix this by commenting the line:

  ```python
  # "text.usetex": True,
  ```
