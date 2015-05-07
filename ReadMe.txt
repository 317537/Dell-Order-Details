############################################################################################
# Author:   Les Fleming
# Date:     07/05/2014
#
# Summary:  An assembly which can be imported into a CLR Integration enabled MS-SQL Server
#           instance. It can be used to query the publicly accessible Dell API to  obtain
#           the original order information relating to a system. Please note that to my
#           understanding the Dell API does not return extended warrranty details.
#
#           Note: Error Handling could be handled better, however I have yet to encounter
#           any issue with it's functionality. I tested this with several hundered tags successfully
#           and repeatedly.        
# Remarks:  ReadDellAssetOrderDetails.zip:  Compressed File containing following files:
#             C# Native Code: ReadDellAssetORderDetails.cs
#             Assembly File:  ReadDellAssetORderDetails.dll
#             sproc_CreateXMLORderRecord.txt: Code example I use to leverage the assembly and 
#             store the response in XML native format.
#             vie_ReadDellWebAPIOrderDetail: Code example which extracts order relevant info
#             in more human readable format.
#             TableStructure.jpg: Example of the table structure I created.
############################################################################################