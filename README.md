# File_Packer_Unpacker

This Application Is Based On Zipping And Unzipping The Directory
By using this project we can fetch data from all files and merge it into one file. As well
as we can also extract all packed file whenever required.

# TECHNOLOGY USED : 
Java Programming

# About This Application :

1) This Application Is Used To Perform Packing And Unpacking Activity For Multiple Types Of Files. 

2) In Case Of Packing Activity I Maintain One File Which Contains Metadata And Data Of Multiple Files From Specified Directory. 

3) In Case Of Unpacking Activity I Extract All Data From Packed Files And According To Its Metadata It Create All Files. 

4) In This Application I Use Java As Frontend As Well As Backend Also For Platform Independency.

Packing Activity :
• In case of Packing activity we accept directory name and file name from user.
• We have to create new regular file as the name specified by the user.
• Now open the directory and traverse each file from that directory. In newly created file
write Metadata as header and actual file data in sequence.
• While writing data perform encryption.
• Each name of file ,its size and checksum should be written in log file which gets
created in system directory.
• After packing display packing report.

UnPacking Activity :
• In case of UnPacking activity we accept packed file name from user.
• for authentication of packed file use any logic like Magic Number.
• Open the packed file in read mode and perform below activity as
• Read header
• From the name specified in header create new file.
• Write data into newly created file from packed file.
• Repeat all above steps till we reached at end of the file unpacked file.
• After unpacking display unpacking report.

Main purpose of this project is to merge large amount of files into one file by avoiding
memory wastage.
We also provide data security by using the concept of Encryption.
For next level data security we add MD5 Checksum check and Primary header check.
