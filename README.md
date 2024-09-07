# bash-cron-backup-script
Scripting Project for IBM Linux Course

type : 'crontab -e' in your terminal and add this to the last line 

" 0 0 * * * /usr/local/bin/backup.sh /home/project/important-documents  /home/project "

  1. my backup script directory : " /usr/local/bin/backup.sh " 
  change this path accordingly 

  2. Path of the documents to be backed up : " /home/project/important-documents "

  3. path of the backed up files. all the files will be archived in this folder : " /home/project "

  4. the file name format is : 'DATE-FOLERNAME".TAR.GZ
     
