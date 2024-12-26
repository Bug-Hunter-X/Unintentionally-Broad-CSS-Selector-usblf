# Unintentionally Broad CSS Selector Bug

This repository demonstrates a common issue in CSS where a selector is too broad, leading to unintended style changes. The `bug.css` file contains the erroneous code, while `bugSolution.css` provides the corrected version.  The problem is that a simple `p` selector affects *all* paragraphs on the page, instead of the intended target.