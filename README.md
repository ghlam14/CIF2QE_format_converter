CIF to Quantum Espresso format converter
script to convert cif file to quantum espresso input, 
after run this script, you should edit the obtained input file according your need, 
if necessary uncomment the magnetic keywords, pseudo_dir path , pseudopotential file name ..



# modified 01/2024 : 
#   fixed warning, pseudo dir , magnetic keywords,
#
# CIF to Quantum Espresso format converter
#               Date: 31-May-2016  Typo fixed; input file can be specified
#                                  with .cif extension (Nick Thompson)
#  Version 1.2  Date: 20-Mar-2015  Bug Fix
#  Version 1.1  Date: 23-Dec-2014  Bug Fix
#               Date: 30-Set-2014  -s option added (F. Zadra)
#  Version 1.0  Date: 15-Mar-2014  First Full conversion
#  Version 0.5  Date: 02-Oct-2013
#  Version 0.4  Date: 12 Jun 2013
#  Version 0.3  Date: 15 Nov 2012
#
# Copyright (C) 2012-2015 Carlo Nervi
# This file is distributed under the terms of the
# GNU General Public License. See the file `License'
# in the root directory of the present distribution,
# or http://www.gnu.org/copyleft/gpl.txt .
#
# Use dos2unix to strip carriage returns at the end of the .cif files!!!!
# Tested with GNU awk v.4 - doesn't work with earlier gawk versions
#
