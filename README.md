# base64pydecoderencoder
Q: What does this tool do? 
A: A python based utility to read a string from a text file and decode encode it using base 64 encryption technique. 

Q: Are there any pre-requisites required to use this utility?
A: All the dependencies are packaged in the utility. 

Q: How to use this utility?
A: Extract the utility to your desktop, where you intend to integrate with the automation tool or any other form of auotmation script. 

Q: What kind of updates I will need to make to the utility?
A: You will need to update the directory of input and output file atline number 9 & 30. 

Q; What are the pre-requistes for using this utility?
A: An input file and output text file. 

Q: What are the business use case where the utility can be utilised?
A: Integrate with any kind of automation script, tool, that has the need to encrypt a string, transport the encrypted string as a password across domains and decrypted at run time for the actual usage. 

Q: Why was this tool built?
A: This tool has been used successfully at three of the below real time project instances:
  * Pass on the Selenium scripts to devops team where security matrix is not implemented and network passwords of real time testers cannot be compromised upon.
  * Limitation of base version of certain automation tools, that do not have the capability of reading an xml file
  * Reduce the dependency on third party encryption and decyption tool for real time processing of money transfer messages in the SAP test applications.
  * In all the instance, the encryption and decryption helped in maintaining the integrity of sensitive information.
  * The approach was socialised with Project Stakeholder and it is only upon agreement that this utility was put to real time project use. 
