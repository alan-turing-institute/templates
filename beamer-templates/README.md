# Beamer Templates
Beamer templates for producing presentations in LaTeX that match ATI house style.

## Getting the template files
Download a \*.zip file with all template files from [here](https://github.com/alan-turing-institute/templates/releases/tag/v0.1.3). The Beamer templates are in the **beamer-templates** subfolder. Alternatively, you can clone this repository using Git (use the **latest-stable** branch if you don't want to be exposed to random changes).

## Installation
You can use the templates without installing them by copying the following **\*.sty** files to the folder containing your presentation. If you want to install the templates for easier use across multiple presentations, copy the following **\*.sty** files to the corresponding subfolders in your Beamer themes directory:
 - **beamerthemeTuring.sty** should be copied to the **themes** subfolder
 - **beamerouterthemeTuring.sty** should be copied to the **outerthemes** subfolder
 - **beamerinnerthemeTuring.sty** should be copied to the **innerthemes** subfolder
 - **beamercolorthemeTuring.sty** should be copied to the **colorthemes** subfolder

 **Note:** The theme needs access to the ATI logo, so you will need to copy the **beamer-templates/images** folder to the folder containing **each** of your presentations, even if you install the **\*.sty** files to your Beamer themes directory.

## Usage
- Copy the **Turing-skeleton-example.tex** file as the base for your presentation. You should also copy the **images** folder with the ATI logos to the folder containing your presentation.
- Choose the light or dark theme by retaining either **\\usetheme{TuringLight}** or **\\usetheme{TuringDark}** (make sure to uncomment your chosen theme if necessary by removing any leading **"%"** at the start of the line. Delete or comment out the other theme (you can comment a line out by placing a **"%"** at the start of the line).
- Set the presentation **title**, **subtitle**, **author** and **date** within the curly braces of the **\\title{}**, **\\subtitle{}**, **\\author{}** and **\\date{}** fields.
- Create your text-based slides following either the single-column or double-column page example skeletons.

## Feedback
All feedback welcome to moreilly at turing dot ac dot uk. Alternatively, feel free to fork the repository, make improvements and submit a pull request.
