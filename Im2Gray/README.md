Prerequisite:
hib file with loaded JPEG images (Here, we have used sampleimages.hib as hib file)

Steps:
This program contains conversion of RGB to Gray.
To run this, download the zip file.
Extract it in your hipi/examples folder
Open terminal at hipi/examples/Im2Gray/build/libs
hadoop jar Im2Gray-1.0-SNAPSHOT.jar Im2Gray sampleimages.hib Img2GrayOp
If the job completes successfully, run:
hadoop fs -copyToLocal Img2GrayOp/part-r-00000 /local_file_path
local_file_path be any path of your local file system with appropriate permissions
