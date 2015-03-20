# master-rankings
PHP Script to automate rankings of best sports performances by master athletes in a certain season.

Version 0.1 of this PHP script was created by Denise van der Linden-Morris to automate sorting tasks when creating master data rankings as a volunteer for the Dutch Athletics Federation.

see also http://www.atletiekunie.nl/3796 to view the latest volunteering needs, and
http://atletiekunie.nl/index.php?page=893 to see the latest rankings

Although Denise has some basic programming knowledge she doesn't work as a programmer on a day-to-day basis and could use some help improving the script. In return she makes the script available to a broader audience so also other people creating rankings can use it to automate their efforts.

Area's for improvement:
- Convert inputfiles (excel, csv) to standard format prior to upload into database
- Eliminate duplicate results for a particular athlete. Each athlete should only appear in the ranking with their best result in a particular season. Right now the script sorts the uploaded results without looking for duplicate entries as no logic is implemented to know which record to delete
