# derwent-database-parser
 A simple python Derwent dataset extractor to parse the Derwent entries in Plain Text format and putting them in an Excel Sheet.

Installation
Clone this repository: git clone https://github.com/SinaAbdipoor/derwent-database-parser.git

Usage
To use this script, run the following command in your terminal:

python convert.py /path/to/derwent_dataset.txt
Replace /path/to/derwent_dataset.txt with the actual path to your Derwent dataset file.

This will create an Excel file named derwent_dataset.xlsx in the same directory as the input file.

Output
The output Excel file will contain a single worksheet with the following headers:

PT
PN
TI
AU
AE
GA
AB
TF
DC
MC
IP
PD
AD
PI
CP
UT
Each row in the worksheet corresponds to an entry in the input file.