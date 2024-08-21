The with_centering argument controls whether the value is centered to zero(median is subtracted) and defults to True, The with_scaling argument controls whether the value us scaled to the IQR (standard deviation set to one)
or not and defukts True.the definition of the scaling range van be specified via the quantile_rangr argument. it takes a tupple of two integers between 0 and 100 and defults to the percentile values os the IQR,
specially(25, 75) and for next step we evalute model with KNN AND Gain Accuracy.
