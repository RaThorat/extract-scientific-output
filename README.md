# Extracting scientific output, if DOIs are provided
This is a code to collect publication information of researchers, if digital object information (DOIs) is available.

There is a need for automation of the publication information of the researchers. Once this information is available, the information can be automatically linked to the relevant researcher. Furthermore, this information can be used for a visualization for finding conflicts of interest with other researchers.

A researcher's publication information will be processed via a free (cross-ref) API, provided DOIs of the publications are available. The json format of Cross-ref API has been edited with python scripts. Excel output file is made of list of authors and number of citations.

Shortcomings The format of output file is not yet as it should be. Two wishes that haven't been fulfilled yet to be: ˆ columns 'family name' and 'given name' side by side and ˆ split year-month column

This project performs analysis on a list of Digital Object Identifiers (DOIs) using the CrossRef API.


# Requirements
  Python 3
  Tkinter (for GUI input)
  crossrefapi (install with pip install crossrefapi)
  openpyxl (for Excel output)
  Pandas (for data manipulation)
  
# Setup
Create an Excel file with a single column of DOIs. The header of the column should be DOIs.

# Usage
Run the script

The script will open a GUI window for you to select the Excel file containing the DOIs.

The script will then retrieve information about the items associated with the DOIs using the CrossRef API. This information includes the authors, publication dates, and other descriptions of the items.

The results will be stored in a Pandas DataFrame and printed to the console.

Finally, the script will use the openpyxl library to save the DataFrame as a new worksheet in the Excel file. The original worksheet with the DOIs will be preserved.
