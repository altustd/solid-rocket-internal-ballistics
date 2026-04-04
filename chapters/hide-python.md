
### Key Option:
- **`#| echo: false`** → This **hides the Python code** but still executes it and shows all output (plots, printed text, tables, etc.).

### Other Useful Options (combine as needed)

You can add these lines right after `{python}`:

```markdown
#| echo: false          # Hide the code
#| warning: false       # Hide warning messages
#| message: false       # Hide print/info messages from libraries
#| fig-cap: "Your figure caption here"   # Add nice caption to plots
#| fig-width: 10
#| fig-height: 6
```

### Alternative Ways

1. **Global setting** (in YAML header of the file or `_quarto.yml`):
   ```yaml
   execute:
     echo: false
   ```
   This hides code in **all** chunks by default.

2. **For a single chunk only** — the `#| echo: false` method above is best.

Would you like me to give you the **updated full Chapter 6** with all Python chunks set to `echo: false` (clean textbook style) while keeping the plots and results visible?

Just say yes and I’ll provide the complete ready-to-paste version of the Performance Modeling chapter with hidden code.