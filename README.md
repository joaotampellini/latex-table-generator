# LaTeX Table Generator

An interactive, web-based tool for building high-quality LaTeX tables with support for:
- Booktabs formatting (`\toprule`, `\midrule`, `\bottomrule`)
- Custom clines with visual toggling
- Column alignment (left, center, right)
- Editable table cells
- Float specifier customization
- Table notes and labels
- Optional `adjustbox` support for wide tables
- Preformatted "econ style" layout with column numbers in appropriate places

## 🔧 Features
- Live LaTeX preview
- Easy addition/removal of rows and columns
- Toggleable alignment settings
- Auto-generated table environment (`table`, `caption`, `label`, etc.)
- Custom cline logic that automatically merges adjacent lines

## Usage
Open the `index.html` file in your browser. No installation required.

## Recommended LaTeX Packages
This tool may generate the following package requirements:
```latex
% Remove '%' to activate if not already included in your preamble
% \usepackage{booktabs}
% \usepackage{threeparttable}
% \usepackage{adjustbox}
