# MLOps Principles Jupyter Book

This repository contains a Jupyter Book about Machine Learning Operations (MLOps) principles, definition, and architecture.

## 📚 Book Structure

The book is built from Jupyter notebooks (not markdown files) and includes:

- **Main Content**: `mlops_principles.ipynb` - The main notebook containing all MLOps content
- **References**: `references.md` - Bibliography and citations
- **Configuration**:
  - `_config.yml` - Book configuration settings
  - `_toc.yml` - Table of contents structure
  - `references.bib` - Bibliography file

## 🛠️ Prerequisites

Make sure you have `jupyter-book` installed:

```bash
# Install using pipx (recommended)
pipx install jupyter-book

# Or using pip in a virtual environment
pip install jupyter-book
```

## 🏗️ Building the Book

To build the book locally:

```bash
# Build the HTML version
jupyter-book build .

# Clean previous builds (if needed)
jupyter-book clean .
```

## 📖 Viewing the Book

After building, you can view your book by:

1. **Opening in browser**: Open `_build/html/index.html` in your web browser
2. **Direct browser URL**:
   ```
   file:///Users/jason/Files/Practice/demo-little-things/mlops-principle/_build/html/index.html
   ```

## 📝 Editing Content

Since this book uses **Jupyter notebooks** (not markdown), you can:

1. **Edit the main content**: Open `mlops_principles.ipynb` in Jupyter Lab/Notebook
2. **Add new chapters**: Create new `.ipynb` files and add them to `_toc.yml`
3. **Update configuration**: Modify `_config.yml` for book settings
4. **Add references**: Update `references.bib` with new citations

## 🔄 Development Workflow

1. Edit your notebook content in Jupyter
2. Save your changes
3. Rebuild the book: `jupyter-book build .`
4. Refresh your browser to see changes

## 📁 Directory Structure

```
mlops-principle/
├── _config.yml              # Book configuration
├── _toc.yml                  # Table of contents
├── mlops_principles.ipynb    # Main content notebook
├── references.md             # References page
├── references.bib            # Bibliography
├── _build/                   # Generated book (don't edit)
│   └── html/                # HTML output
└── README.md                # This file
```

## 🚀 Next Steps

To enhance your Jupyter Book:

1. **Split content**: Break the large notebook into smaller, focused chapters
2. **Add interactivity**: Include interactive widgets and plots
3. **Publish online**: Deploy to GitHub Pages, Netlify, or other hosting services
4. **Add more content**: Create additional notebooks for different topics

## 📚 Resources

- [Jupyter Book Documentation](https://jupyterbook.org/)
- [MyST Markdown Guide](https://myst-parser.readthedocs.io/)
- [Jupyter Book Gallery](https://executablebooks.org/en/latest/gallery.html)
