# ORF307 Companion
Supporting material for Princeton ORF307

You can (non-interactively) browse all the notebooks in this repo on [nbviewer](https://nbviewer.jupyter.org/github/ORF307/companion/tree/main/)

## Troubleshooting

- `Failed to process string with tex because latex could not be found` when generating plots.
  You most likely do not have latex installed (not present by default in colab). You can simply fix this by commenting the line:

  ```python
  # "text.usetex": True,
  ```
