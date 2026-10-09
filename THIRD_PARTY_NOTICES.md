# Third-party notices and licensing scope

This repository combines Palermo Penano's original student contributions with
Udacity course material and other third-party material. The root LICENSE
covers only the explicitly identified original contributions. It is not a
repository-wide permission to redistribute every file.

## Udacity machine-learning coursework: CC BY-NC-ND 4.0

Source: [udacity/machine-learning at commit 48178d7](https://github.com/udacity/machine-learning/blob/48178d734ba9e97291498b5ebc57639a71f6548c/README.md).
This historical source predates the repository's 2018 coursework, and the
current upstream README carries the same license designation.

The original source notice is reproduced here:

```html
<a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-nd/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/">Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License</a>. Please refer to [Udacity Terms of Service](https://www.udacity.com/legal) for further information.
```

License link: http://creativecommons.org/licenses/by-nc-nd/4.0/

The following material is adapted from or accompanies Udacity's coursework:
- boston_housing/ corresponds to upstream projects/boston_housing/.
- customer_segments/ corresponds to upstream projects/customer_segments/.
- finding_donors/ corresponds to upstream projects/finding_donors/.
- titanic_survival_exploration/ corresponds to upstream
  projects/titanic_survival_exploration/.
- naive_bayes_spam.ipynb explicitly credits the upstream
  projects/practice_projects/naive_bayes_tutorial/Naive_Bayes_tutorial.ipynb
  tutorial.

[Historical source tree](https://github.com/udacity/machine-learning/tree/48178d734ba9e97291498b5ebc57639a71f6548c/projects)

Palermo's notebooks add student solutions, analysis, implementation changes,
and outputs to these sources. The HTML reports reproduce modified notebooks.
This notice records those changes; it does not supply permission to distribute
adapted course material. The MIT grant for Palermo's original contributions
does not relicense the Udacity portions or remove their NonCommercial and
NoDerivatives restrictions. Permission to distribute combined or adapted
coursework has not been established by this documentation. Obtain the needed
permission from the rights holder before relying on such a right.

## Udacity dog-project and deep-learning code: MIT

The pre-existing [dog-project/LICENSE.txt](dog-project/LICENSE.txt) is preserved
unchanged. Its contents match the source
[udacity/dog-project LICENSE.txt](https://github.com/udacity/dog-project/blob/1c034a6e24dc6228cdd8e76faedb8445e986f378/LICENSE.txt).

The notebook in extras/student-admissiomns-keras/ is based on
[udacity/deep-learning/student-admissions-keras](https://github.com/udacity/deep-learning/tree/6d8bdf6596a1243cf95981ccc815e4ab49bf5cc8/student-admissions-keras).
The MIT notice missing from that copied code is reproduced verbatim below
from [its source LICENSE](https://github.com/udacity/deep-learning/blob/6d8bdf6596a1243cf95981ccc815e4ab49bf5cc8/LICENSE).
The dog-project and deep-learning license texts are identical.

```text
Copyright (c) 2017 Udacity, Inc.

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

This Udacity MIT notice applies to the relevant Udacity code and documentation,
not to independently owned datasets, images, libraries, or model assets.

## OpenCV / Intel face cascade

dog-project/haarcascades/haarcascade_frontalface_alt.xml contains its own
Intel License Agreement for the Open Source Computer Vision Library, including
Copyright (C) 2000, Intel Corporation, all rights reserved.
That full embedded notice remains unchanged and controls that component.
It requires notice retention and restricts use of Intel's name for endorsement.
The component is not relicensed under Palermo's MIT grant.

[Preserved embedded notice](https://github.com/palpen/udacity_ml_engineer_projects/blob/fb0e17e8929f5801582edca780ac27940af7ca9e/dog-project/haarcascades/haarcascade_frontalface_alt.xml)

## Datasets, images, outputs, and other exclusions

No new permission is granted here for:
- boston_housing/housing.csv, sourced from the Boston Housing data described
  in that project's README;
- customer_segments/customers.csv, sourced from the UCI Wholesale Customers
  data described in that project's README;
- finding_donors/census.csv, sourced from the census-income data described in
  that project's README;
- titanic_survival_exploration/titanic_data.csv, identified in its README as
  data supplied by Udacity;
- extras/student-admissiomns-keras/student_data.csv, matching the upstream
  deep-learning dataset whose notebook credits UCLA;
- externally downloaded SMS, dog, or human-image datasets; dog-project/images/;
  pretrained model files; embedded notebook or report assets; or external
  dependencies.

These materials may have their own licenses or other rights restrictions.
Source attribution alone does not establish permission. Dataset, image, and
transitive dependency rights have not been fully cleared.

Existing licenses, source attributions, and embedded notices are preserved.
No notebook, Python source, data file, image, model, or generated report is
modified by this licensing documentation.
