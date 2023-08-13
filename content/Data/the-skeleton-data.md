---
title: "The Skeleton Data"
---

[Download the Skeleton Data](../SkeletonDatacomplete.txt) (plain text).

Estimating the age at death from skeletal remains is a common problem in forensic anthropology. Anthropologists have devised different methods for estimating age. In adult skeletal remains, these methods often rely on examination of the wear and deterioration in certain bones.

The skeleton data were provided by Catherine Merritt, a biological anthropologist at the University of Toronto. Catherine is interested in how the accuracy of several age estimation methods is associated with physical characteristics of the people. She has used a number of methods to estimate the age at death of several hundred skeletons of known age, so that she can assess the accuracy of the estimated age. The skeleton data are a randomly selected subset of 400 of the skeletons Catherine has investigated and two age estimation methods:

1. The method of Di Gangi et al. uses the first rib to determine the most likely age of death.
2. The Suchey-Brooks method uses the pubic bone to determine the most likely age of death. It is the most commonly used method. In our dataset, for two of the skeletons the pubic bone was not available so the estimates of age at death using the Suchey-Brooks method are missing for these skeletons.

A possibly important distinction between these two methods is that the pubic bone is part of the pelvis, which is a weight-bearing part of the human skeleton, while the ribs are not weight-bearing.

For the analysis of these data, we will investigate the error in age estimation. The error in age estimation is the difference between the estimated age and actual age at death, measured in years. Possible questions we can investigate with these data include:

- How accurately does each of these two methods estimate age at death?
- How does the error in age estimation differ between the two methods?
- Does the error in age estimation vary with the actual age at death?
- Does the error in age estimation tend to be different for males and females?
- Does variation in body mass index result in variation in deterioration of bones, and as a result, is there a relationship between error in age estimation and body mass index?

The skeleton data are available in the [data file SkeletonDatacomplete.txt](../SkeletonDatacomplete.txt). In this file, the first row is a list of the variable names. Starting on the second row, there is one row for each skeleton. Variables on each row are separated by spaces. The variables on each row are:

- **Sex** — Sex is 1 for males and 2 for females
- **BMIcat** — The body mass index, categorized as underweight, normal, overweight, or obese.
- **BMIquant** — The body mass index is a quantitative variable, in km/m2.
- **Age** — The actual age at death in years.
- **DGestimate** — The estimated age at death using the method of Di Gangi et al. in years.
- **DGerror** — The estimated age at death using the method of Di Gangi el al. minus the actual age at death in years.
- **SBestimate** — The estimated age at death using the Suchey-Brooks method, in years.
- **DGerror** — The estimated age at death using the Suchey-Brooks method minus the actual age at death, in years.