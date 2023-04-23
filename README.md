# GIT Homework 1 "XML"

21. Create an external repository named XML.  
`` 

22. Clone XML repository to local machine.  
`git clone git@github.com:AlekseiRbo/XML.git` 

23. Inside the local XML create a "new.xml" file.   
`touch new.xml`

24. Add file under git.  
`git add .`

25. Commit file.  
`git commit -m "Add new.xml"`

26. Push file to external GitHub repository.  
`git push`  

27. Edit the content of the "new.xml" file - write information about yourself (full name, age, number of pets, future desired salary). Write everything in XML format.  
`vim new.xml`  
```
<?xml version="1.0" encoding="UTF-8"?>
	<user>
		<user_name>Riaboshapko Aleksei</user_name>>
		<user_age>28</user_age>
		<user_animal>0</user_animal>
		<user_salary>1000</user_salary>
	</user> 
```
28. Push changes to an external repository.  
`git commit -am "Add diff new.xml`  
`git push`  

29. Create preferences.xml file  
`touch preferences.xml`  

30. In the preferences.xml file, add information about your preferences (Favorite movie, favorite series, favorite food, favorite season, side you would like to visit) in XML format.  
`vim preferences.xml`  
```
<?xml version="1.0" encoding="UTF-8"?>
	<user>
		<user_movie>John Wick</user_movie>
		<user_soap_opera>The Walking Dead</user_soap_opera>
		<user_food>French_meat, Pork_skewers</user_food>
		<user_season>I like all seasons</user_season>
		<user_country>Germany</user_country>
	</user>
```  

31. Create a sklls.xml file to add information about the skills that will be studied in the course in XML format.  
`vim sklls.xml`  
```
<?xml version="1.0" encoding="UTF-8"?>
	<user>
		<user_soft_skills>Git, GitHub, Postman_API, SQL, SOAP_API, and etc</user_soft_skills>
		<user_hard_skills>attentiveness, multitasking, perseverance, skill to work in team</user_hard_skills> 
	</user>
```  

32. Make a commit in one line.  


33.  Send 2 files at once to an external repository.  
`git commit -am "Add diff "preferences.json" and "sklls.xml"`  
`git push`  

34. On the web interface, create a bug_report.xml file.  
Click in the repository `Add file` then `Create new file` in field "Name your file..." enter "bug_report.xml"  

35. Make Commit changes (save) changes on the web interface.  
In field "Update README.md" enter ***changes*** then click `Commit changes`  

36. On the web interface, modify the bug_report.xml file, add a bug report in XML format.  
Go to file "bug_report.xml" click `Edit this file`, insert xml file:  
```
<?xml version="1.0" encoding="UTF-8"?>
  <bug_report>
      <Severity></Severity>
      <Environment></Environment>
      <Title></Title>
      <Steps></Steps>
      <Expected_Result></Expected_Result>
      <Actual_Result></Actual_Result>
      <Link></Link>
      <License></License>
      <Role_(unregistered, unauthorized, authorized, All)></Role_(unregistered, unauthorized, authorized, All)>
      <Telegram_@nick. Bug_started></Telegram_@nick. Bug_started>
      <Telegram_@nick. Bug_reproduced></Telegram_@nick. Bug_reproduced>
      <Telegram_@nick. Bug_did_not_reproduce></Telegram_@nick. Bug_did_not_reproduce>
      <Bug_did_not_reproduce_(environment)></Bug_did_not_reproduce_(environment)>
  </bug_report>
```

37. Make Commit changes (save) changes on the web interface.  
In field "Update README.md" enter ***changes*** then click `Commit changes`  

38. Synchronize external and local XML repository.  
`git pull` 
