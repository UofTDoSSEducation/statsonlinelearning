---
title: "The Five Number Summary"
date: 2023-08-10T16:53:35-04:00
draft: false
---

The five number summary gives a quick look at the features of numerical variables. In this video you will be introduced to the statistics that comprise the five number summary and how they can be displayed graphically in a box plot.

Stream the video without the embedded quiz questions by clicking on the video link below. Closed captions are available.

{{< youtube CdmcWa9V6Yk >}}

[Notes on the video: The Five Number Summary](../1-1-Five-Number-Summary.pdf)

### A point to consider for this video:

**Calculating quartiles and percentiles:**  
Finding quartiles typically necessitates interpolating between two of the data values. Many ways have been proposed to do this, and the various methods have different desirable technical properties. As an example, consider the ordered data consisting of the following quiz scores for 8 students (out of 10): {5, 5, 6, 7, 8, 9, 9, 10}.

The median is the average of the 4th and 5th data value, which is 7.5.

One common method to estimate the 1st quartile is to find the median of the lower half of the data. That is, find the median of the four data values {5, 5, 6, 7}, which is 5.5.

Another common method is to calculate the position, or rank, of the quartile in a dataset that has been ordered from smallest to largest.  For an estimate of the first quartile of a dataset containing n values, find the position using the formula
*position=quartile ⁄ 100×(n-1)+1*, where *quartile* is 25 for the first quartile, 50 for the median, and 75 for the third quartile.

Then for the 1st quartile of this simple dataset, *position=0.25×7+1=2.75*.

And so the estimate of the 1st quartile is the value that is three-quarters of the way between the 2nd and 3rd data value, or 5.75 for these data.

This formula for finding the position of a quartile can be extended to any percentile. Definitions of percentile can vary slightly, but the important thing to keep in mind when talking about a percentile is how to interpret it. As an example, the  90th percentile gives an estimate of the value that is greater than or equal to 90% of the data. One method of estimating it is to calculate its position in the dataset, using the formula above, plugging in 90 for quartile. (Although the 90th percentile isn’t a quartile, the formula works for any percentile.)

Any of the other methods to estimate a quartile or other percentile will give a similar answer and any can be used. Much more important than the details of the calculation is to be able to properly interpret its meaning. Here’s an example:

*Suppose a class of students write an exam, and the 3rd quartile of their grades is 80. A student writes the test the next day, and gets a grade of 75. What can we say about this student’s grade compared to the rest of the class?*