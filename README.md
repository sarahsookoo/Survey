I created a survey in HTML with an action attribute of insert.php and a POST method. When the survey is submitted, it redirects to the php file which extracts the survey answers and stores them in my database. This was created for me to practice my full stack skills.

# How to use
- download xampp
- go to xampp control panel and turn on apache and mysql
- clone this repo and copy the files
- go to :C/xampp/htdocs and create a folder. Paste the files into this folder.
- go to localhost/myphpadmin in your browser and create a database named surveys
- in this database, create a table named survey_one with 3 columns: name, answer, comments
- go to localhost/<foldername><index.php> in your browser and fill out the survey
- refresh the localhost/myphpadmin and you should see the survey data