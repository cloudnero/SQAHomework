What are the basic concepts of DFT?

DFT is short for Data Flow Testing.

  DFT could find out data dependency and optimize performance problems in program.
DFT is consist of Data Flow (Data Dependency) and Data slice. There are also tow
kinds of operator in DFT, Define (D) and Use (U).D means create, initialize and 
assign data. And U involves computational and predicate characteristics of data 
operations. So when testing we should focus on D and relate U.
  To analysis data dependency problem, we can use U-U and D-U. Whill if someone 
find D-D or U-D, his or her program will be wrong. Someone who should focus on this
situation.
  DFT focuses on testing D-U relations. We can use DDG to help us to analysis software.
