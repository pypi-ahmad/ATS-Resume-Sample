# 📄 ATS-Optimized LaTeX Resume Template

![LaTeX](https://img.shields.io/badge/LaTeX-Project-47A141?style=flat&logo=latex&logoColor=white)
![ATS Friendly](https://img.shields.io/badge/ATS-Optimized-blue)
![License](https://img.shields.io/badge/License-MIT-yellow.svg)

A professional, clean, and **ATS-parsable** resume template designed to help you get past automated filters while looking elegant for human recruiters.

## 🚀 Features

*   **ATS-Ready**: Specifically configured with `cmap` and `glyphtounicode` to ensure Applicant Tracking Systems can correctly parse the text (PDF copy-paste friendly).
*   **Machine Readable**: metadata and font encoding are optimized for parsing algorithms.
*   **Professional Design**: Uses the clean **Source Sans Pro** font family with subtle color accents.
*   **Clickable Links**: Integrated `hyperref` for Email, LinkedIn, GitHub, and Portfolio links.
*   **Customizable**: Modular structure makes it easy to add/remove sections (Experience, Projects, Skills, Education).
*   **Metadata**: Automatically sets PDF Author, Title, and Keywords for a professional finish.

## 📂 Project Structure

```bash
.
├── main.tex               # The LaTeX source code
├── ATS_Resume_Sample.pdf  # Sample output preview
└── README.md              # Documentation
```

## 🛠️ How to Use

### Option 1: Overleaf (Recommended)
1.  Create a new project on [Overleaf](https://www.overleaf.com/).
2.  Upload `main.tex` to your project.
3.  Set the compiler to **pdfLaTeX**.
4.  Edit the placeholders (e.g., `[Your Name]`, `[Company Name]`) with your details.
5.  Hit **Recompile**.

### Option 2: Local Installation
Ensure you have a TeX distribution installed (e.g., TeX Live, MiKTeX, MacTeX).

1.  Clone this repository:
    ```bash
    git clone https://github.com/yourusername/ATS-Resume-Sample.git
    ```
2.  Open `main.tex` in your favorite LaTeX editor (VS Code with LaTeX Workshop, TeXShop, etc.).
3.  Compile using `pdflatex`:
    ```bash
    pdflatex main.tex
    ```

## 📝 Customization Tips

*   **Colors**: Change the accent color by modifying the HTML code in line `\definecolor{primaryLinks}{HTML}{145680}`.
*   **Fonts**: The template uses `sourcesanspro`. You can switch to `lato`, `roboto`, or standard LaTeX fonts if preferred.
*   **Icons**: Uses `fontawesome5`. You can find more icons [here](https://fontawesome.com/).

## 🤝 Contributing

Feel free to fork this project and submit pull requests if you have improvements for layout or ATS compatibility!

## 📜 License

This project is licensed under the MIT License - feel free to use it for your personal resume.