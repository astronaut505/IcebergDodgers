Editor.md
Open source online Markdown editor.

# Titanic Survival Prediction
​
This project is a part of my machine learning class assignment, where the goal was to predict the survival of passengers on the Titanic based on various features.
## Dataset
​
The dataset used for this project is the well-known Titanic dataset, which contains information about passengers, including:
​
- Passenger class
- Name
- Gender
- Age
- Number of siblings or spouses aboard
- Number of parents or children aboard
- Fare
- Initial (a derived feature)
- Family size (a derived feature)
- Age group (a derived feature)
- Fare per person (a derived feature)
- IsAlone (a derived feature)
- Fare per person range (a derived feature)
​
## Machine Learning Model
​
The primary machine learning algorithm used for this project is Logistic Regression. The logistic regression model is trained on the dataset to predict passenger survival. Feature importance is analyzed to understand which factors played a significant role in determining survival.
​
## Results
​
The project achieved an accuracy of approximately 78.69% using Logistic Regression, as determined through cross-validation. 
​
Feel free to experiment with different machine learning models and preprocessing techniques to improve prediction accuracy.
​
## Credits
​
- This project was completed as an assignment for [Machine Learning II] at University of Warsaw.
- The Titanic dataset is available in /data/
​
Titanic Survival Prediction
This project is a part of my machine learning class assignment, where the goal was to predict the survival of passengers on the Titanic based on various features.

Dataset
The dataset used for this project is the well-known Titanic dataset, which contains information about passengers, including:

Passenger class
Name
Gender
Age
Number of siblings or spouses aboard
Number of parents or children aboard
Fare
Initial (a derived feature)
Family size (a derived feature)
Age group (a derived feature)
Fare per person (a derived feature)
IsAlone (a derived feature)
Fare per person range (a derived feature)
Machine Learning Model
The primary machine learning algorithm used for this project is Logistic Regression. The logistic regression model is trained on the dataset to predict passenger survival. Feature importance is analyzed to understand which factors played a significant role in determining survival.

Results
The project achieved an accuracy of approximately 78.69% using Logistic Regression, as determined through cross-validation.

Feel free to experiment with different machine learning models and preprocessing techniques to improve prediction accuracy.

Credits
This project was completed as an assignment for [Machine Learning II] at University of Warsaw.
The Titanic dataset is available in /data/
Example
<link rel="stylesheet" href="editormd/css/editormd.css" />
<div id="test-editor">
    <textarea style="display:none;">### Editor.md

**Editor.md**: The open source embeddable online markdown editor, based on CodeMirror & jQuery & Marked.
    </textarea>
</div>
<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/1.11.3/jquery.min.js"></script>
<script src="editormd/editormd.min.js"></script>
<script type="text/javascript">
    $(function() {
        var editor = editormd("test-editor", {
            // width  : "100%",
            // height : "100%",
            path   : "editormd/lib/"
        });
    });
</script>Copy
More Examples >>

Features
Support Standard Markdown / CommonMark and GFM(GitHub Flavored Markdown);
Full-featured: Real-time Preview, Image (cross-domain) upload, Preformatted text/Code blocks/Tables insert, Code fold, Search replace, Read only, Themes, Multi-languages, L18n, HTML entities, Code syntax highlighting...;
Markdown Extras : Support ToC (Table of Contents), Emoji, Task lists, @Links...;
Support TeX (LaTeX expressions, Based on KaTeX), Flowchart and Sequence Diagram of Markdown extended syntax;
Support identification, interpretation, fliter of the HTML tags;
Support AMD/CMD (Require.js & Sea.js) Module Loader, and Custom/define editor plugins;
Compatible with all major browsers (IE8+), compatible Zepto.js and iPad;
Support Custom theme styles;
Download & install
Latest version: v1.5.0，Update: 2015-06-09



 


Or NPM install:

npm install editor.md



Or Bower install:

bower install editor.md




Change logs:

CHANGES

Dependents
Projects :

CodeMirror
marked
jQuery
FontAwesome
github-markdown.css
KaTeX
Rephael.js
prettify.js
flowchart.js
sequence-diagram.js
Prefixes.scss

Development tools :

Visual Studio Code
Sass/Scss
Gulp.js
License
Editor.md follows the MIT License, Anyone can freely use.





Fork me on Github :







Users

 Contact Us: editor.md@ipandao.com


Editor.md
Copyright © 2015-2019 Editor.md, MIT license.

Design & Develop By: Pandao     