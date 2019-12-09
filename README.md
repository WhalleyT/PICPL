# PICPL
GPU accelerated combinatorial peptide library peptide scanning

## Installation
A zip file of the executables can be downloaded from the RELEASES under the ASSETS. The executable will run on any of the 3 platforms (Linux, Windows, MacOS). A sample of protein sequences (testdata.fasta) and combinatorial peptide library data
(CPL.txt) is included in the executable to test the codes. 

## Usage

The CPL database scan can be ran as such:

```./CPL <cpl scan file> <fasta> <number of results>```

and the peptide ranking:

```./theoretical_rank <cpl scan file> <peptide>```

The database scoring executables can be found in the folder "score_database" and the ranking executable in "rank".

To run the test data, enter the PICPL directory and run:

```./score_database/PICPL_cuda data/testdata.fasta data/CPL.txt 5000```

## License
Combinatorial Peptide Library, © 2019, The University of Warwick and Cardiff University (the "Software"). The Software remains the property of the University of Warwick and Cardiff University ("the Universities"). The Software is hosted "AS IS" under this Licence solely for non-commercial use in the hope that it will be useful, but in order that the Universities as charitable foundations protect their assets for the benefit of their educational and research purposes, the Universities make clear that no condition is made or to be implied, nor is any warranty given or to be implied, as to the accuracy of the Software, or that it will be suitable for any particular purpose or for use under any specific conditions. Furthermore, the Universities disclaim all responsibility for the use which is made of the Software. It further disclaims any liability for the outcomes arising from using the Software. The Licensee agrees to indemnify the Universities and hold the Universities harmless from and against any and all claims, damages and liabilities asserted by third parties (including claims for negligence) which arise directly or indirectly from the use of the Software. No part of the Software may be reproduced, modified, transmitted or transferred in any form or by any means, electronic or mechanical, without the express permission of the Universities. You may be held legally responsible for any copyright infringement that is caused or encouraged by your failure to abide by these terms and conditions. You are not permitted under this Licence to use this Software commercially. Use for which any financial return is received shall be defined as commercial use, and includes (1) use of the Software or any derivative of it for research with the final aim of developing software products for sale or license to a third party (2) use of the Software to provide any service to an external organisation for which payment is received. If you are interested in using the Software commercially, please contact the Cardiff University Technology Transfer Office (“TTO”). Contact details are: technologytransfer@Cardiff.ac.uk quoting reference Combinatorial Peptide Library. If you are in any doubt if your use constitutes commercial use, contact the Cardiff University TTO.

This Licence is governed by the laws of England and Wales and is subject to the exclusive jurisdiction of the courts of England and Wales

## Citations
Thomas Whalley, Garry Dolton, Paul E. Brown, Aaron  Wall, Linda Wooldridge, Hugo van den Berg, Anna Fuller, Jade Hopkins, Michael D. Crowther, Meriem Attaf, Robin R., Knight, David K. Cole, Mark Peakman, Andrew K. Sewell and Barbara Szomolay, 
GPU-Accelerated Discovery of Pathogen-Derived Molecular Mimics of a T-cell Insulin Epitope, 2019.

## Contact
For enquiries about the Sofware or fungal/bacterial databases from the manuscript please contact Barbara Szomolay (szomolayB@cardiff.ac.uk).
