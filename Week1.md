# Cleaning_data-course
Downloading files:
  Get/set your working directory:
    -Two main commands are getwd() and setwd()
    -Be aware of relative vs absolute path:
      -Relative: -setwd("./data"), setwd("../")
      -Absolute: setwd("/User/SeanLiao/data/")
  Checing for and creating directories:
    -file.exists("directoryname") will check if the directory exists
    -dir.create("directoryname") will create a directory if it doesn't exist:
      if(!file.exists("data")){
        dir.create("data")
      }
  Getting data from the internet-download.file()
