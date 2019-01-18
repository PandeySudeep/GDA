# Does Gaussian Discriminant Analysis perform better than Logistic Regression?

## Overview

I took two sets of data - one with Multivariate Gaussian Distribution and another non-gaussian. I then modeled linear classifier on both the sets with Gaussian Discriminant Analysis as well as Logistic Regression.

### GDA on gaussian data:
<p><img src="gda_gaussian.PNG" title="image1" alt="Classifier1"></a></p>

### Logistic Regression on gaussian data:
<p><img src="logistic_gaussian.PNG" title="image2" alt="Classifier2"></a></p>

<p style="font-weight:bold">If p(x|y) is Gaussian, then p(y|x) is also logistic, hence both techniques output good classifiers. However, GDA performs better.</p>

### GDA on non-gaussian data:
<p><img src="gda_non-gaussian.PNG" title="image3" alt="Classifier3"></a></p>

### Logistic Regression on non-gaussian data:
<p><img src="logistic_non-gaussian.PNG" title="image4" alt="Classifier4"></a></p>

#### If p(y|x) is logistic, p(x|y) might not be Gaussian. Logistic regression should be chosen.

