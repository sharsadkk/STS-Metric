## Project Description
STS-METRIC is a Python desktop GUI application that allows user to load configuration parameters and generate engineering performance metrics for STS cranes. By fine-tuning the configuration parameters, users can analyze crane structure behavior and adjust the values of constants as needed. 
## Installation and updating
Use the STSMetric_WINDOWS_setup.exe installer provided with product key for installation and updates. Rerun the installer to check for and install updates.
## Usage
To utilize the software, we need to provide three input files: a `config.xlsx` file containing information about struc-variables and other crane-specific user-input values, a `keyname.csv` file related to the crane, and trace log files (`.trc`). The application then computes crane metrics using the high-level steps outlined below:

1.  Decode data stored in binary trace files.

2.  Define each metric within a cycle (lifting, traveling, full cycle, or automation cycle). To begin metric calculations, binary data must be decoded, and a defined cycle must be extracted from the decoded data.
3.  Report the calculated metric for each cycle present in the decoded data in an Excel table format. Each row relates to a cycle, and the columns represent the metrics for that cycle.
## Information
For any queries, please contact sharsad.karakuni@mtu.ie or john.barry@liebherr.ie
## License
[MIT](https://choosealicense.com/licenses/mit/)
