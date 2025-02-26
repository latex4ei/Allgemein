______________________________________________________________________

## title: "LaTeX4Ei Template: Compile Beautiful Cheat Sheets in LaTeX" nav_title: "LaTeX4Ei Template" description: "Clone our CheatsheetTemplate repository, update the file name, and use our GitHub Action to compile professional cheat sheets with LaTeX4Ei."

![CheatsheetTemplate](/img/CheatsheetTemplate.png)

The **LaTeX4Ei Template** is the solution for writing beautiful cheat sheets. In this section we explain how to get started using our template.

## Example

Here is our documentation PDF that demonstrates the template’s output:

<iframe src="https://latex4ei.github.io/latex4ei-packages/LaTeX4EI-Template-Documentation.pdf" style="width: 100%; height: 510px; aspect-ratio: 297 / 210;"
  frameborder="0">
  This browser does not support PDFs. Please download the PDF <a href="https://latex4ei.github.io/latex4ei-packages/LaTeX4EI-Template-Documentation.pdf">here</a>.
</iframe>

## Using the Template

### 1. Setting Up Your Repository

1. **Create Your Repository:**
   Click the **"Use this template"** button on our [CheatsheetTemplate](https://github.com/latex4ei/CheatsheetTemplate) GitHub repository to create a new repository. Alternatively, you can clone the repository.

1. **Download the Required Package:**
   To compile locally, you must have the latest LaTeX4Ei package. Get it from:
   [https://github.com/latex4ei/latex4ei-packages/releases](https://github.com/latex4ei/latex4ei-packages/releases)

1. **Place the Package:**
   Unzip `latex4ei.zip` (from the package download) and move the entire `latex4ei` folder into the root of your repository.

### 2. Update Environment (if using GitHub Actions)

1. **Rename Your File:**  Rename the provided `CheatsheetTemplate.tex` file to exactly match the name of your repository. This ensures proper integration with our build process.

1. **Update Build Files:**
   Follow these steps to automatically update the build files:

   1. Go to your repository on GitHub.
   1. Click on the **Actions** tab.
   1. Locate and trigger the **"Update README and LaTeX Build File"** action.

This action automatically updates your README and the CMake build file with your repository’s name, ensuring your build configuration is set up correctly.

### 3. Compile Your Cheat Sheet

Now you can start adding content to your `.tex` file. You can compile your document:

- **Locally:** With the `latex4ei` folder in your repository root, compile using your preferred LaTeX compiler (e.g., `pdflatex`).

- **Via GitHub Actions:** When you push your changes, our GitHub action will automatically compile your cheat sheet. The generated PDF is available in the `gh-pages` branch or as an artifact of the workflow run.

______________________________________________________________________

## Questions?

For questions or contributions, visit our [GitHub](https://github.com/latex4ei) or contact us at [info@latex4ei.de](mailto:info@latex4ei.de).
