Linux code for finding number of files, the largest file etc, in the file TestDataForExercises.tgz

Ex4_1.bsh :

 count the number of files in this directory after untar and unziping TestDataForExercises and print out the name of the file with the largest number of entries 
 
Ex4_2.bsh :

 The filenames follow the pattern \
 nveTest_screw_n111_bCA_Al_x100_y010_wVtypes.<snapshotNum>.chkpt \
 Gives the header info of each individual file and output it to a new file with the name \
 nveTest_screw_n111_bCA_Al_x100_y010_wVtypes.<snapshotNum>.chkpt.headerInfo \
 Output only the data lines to a new file with the name \
 nveTest_screw_n111_bCA_Al_x100_y010_wVtypes.<snapshotNum>.chkpt.data

Ex4_3.bsh :

  Gives information of the simulation box (lines 3,4,5) of each snapshot in file boxInfo.txt

Ex4_4.bsh :

  Check if the file exists in the current directory. \
  • If NO: then prints an appropriate error message and exits. \
  • If YES: then read the header of the file and print out the simulation box size, snapshot \
    number, size of the file in human readable form, and number of lines in file 
