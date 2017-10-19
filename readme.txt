(1) configuring the ftp server
	-changing the config settings(vsftpd.config)
(2)Five sample csv are kept in one folder (i.e Downloads) in my system,
   a java code jar file is prepared to check the csv files.
	-Above written stuff works with crontab (a regular check of 30 min for the csv files)
(3)Logging of file timestamp
	- A command which displays the timestamp is directed from cron job to a text file(cronlog.txt)
(4)Deleting the older files
