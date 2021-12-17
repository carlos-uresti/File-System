# File-System
						      Supported Commands
	
Command:	         Usage:								              Description:

put 		      put <filename> 				  		        Copy the local file to the filesystem image

get 		      get <filename> 				  		        Retrieve the file from the filesystem image

del 		      get <filename> <newfilename>  		  			Retrieve the file form the file system image 
											and place it in the file named <newfilename>

list 		      list [-h] 					  	        List the files in the file system image

df 		      df 							        Display the amount of disk space left in the 
										        file system
open 		      open <file image name> 		  		                Open a file system image

close 		      close <file image name> 	  		                        Close the currently opened file system

createfs 	      createfs < disk image name >  		                        Create a new file system image

savefs 		      savefs 						  		Save the current file system image

attrib 		      attrib [+attribute] [ -attribute] <filename>	                Set or remove the attribute for the file
			         
quit                  quit                                                              Quit the application
