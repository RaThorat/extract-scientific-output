# Extracting scientific output, if DOIs are provided
This is a code to collect publication information of researchers, if digital object information (DOIs) is available.

There is a need for automation of the publication information of the researchers. Once this information is available, the information can be automatically linked to the relevant researcher. Furthermore, this information can be used for a visualization for finding conflicts of interest with other researchers.

A researcher's publication information will be processed via a free (cross-ref) API, provided DOIs of the publications are available. The json format of Cross-ref API has been edited with python scripts. Excel output file is made of list of authors and number of citations.

Shortcomings The format of output file is not yet as it should be. Two wishes that haven't been fulfilled yet to be: ˆ columns 'family name' and 'given name' side by side and ˆ split year-month column


