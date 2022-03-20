# PythonPDFTableExtractor
a python script that extracts table and output as csv or xlsx from PDF files

# Project Overview
- reading PDF files with Camelot and extract information for specified areas
- process loaded information with pandas and output as csv and xlsx
- the project can be scalable to other pdf series that have fixed format
- camelot has more flexibility to tweak table extraction, hence serving as a backup solution incase other tool fails to precess the pdf

# Project Demo
- Original input: a pdf containining tables
![orginalPDF](doc/demo-originalPDF.JPG)
- Excel & csv output will be generated in the same directoty upon running the program
![directory](doc/demo-directory.JPG)
    - excel sample
    - ![directory](doc/processedXlsx.JPG)
- (Additional) data in dataframe can further be drew as plots
![directory](doc/demo-plot.JPG)
