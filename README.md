# id-vars-from-resp-data

Code to identify relevant variables from dose response data

This code selects candidate variables by first fitting the data with sigmoidal functions to identify steep increases/decreases of the responses. Then, the variables that are reported are those that present abrupt transcriptional changes that overlap with the region where a phenotypic outcome changes.
