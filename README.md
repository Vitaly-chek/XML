# HW_2 : XML

1. Create an external repository called XML;

2. Clone the XML repository to the local computer - `git clone URL`;

3. Inside the local XML create a file “new.xml” - `git touch new.xml`;

4. Add a file under git - `git add .`;

5. Commit the file - `git commit -m "create new file"`;

6. Send a file to an external GitHub repository - `git push`;

7. Edit the content of the “new.xml” file - write information about yourself (name, age, number of pets,
	future desired salary). Everything is written in XML format:

```
<?xml version="1.0" encoding="UTF-8"?>
<info>
	<about_me>
		<name> Vitaly </name>
		<lastname> Krivoruchek </lastname>
		<age> 23 </age>
		<pets> 3 </pets>
	</about_me>
	<work>
		<position> QA Engineer </position>
		<salary> 600 </salary>
		<currency> USD </salary>
	</work>
</info>
```

8. Push changes to an external repository - `git commit -am "updated file" / git push`;

9. Create file preferences.xml - `touch preferences.xml`;

10. In the preferences.xml file, add information about your preferences (Favorite movie,
	favorite TV series, favorite food, favorite season, side you would like to visit) in XML format:

```
<?xml version="1.0" encoding="UTF-8"?>
<preference>
	<favorite_movie> The Wolf of Wall Street </favorite_movie>
	<favorite_series> The 100 </favorite_series>
	<favorite_food>
		<1> Okroshka </1>
		<2> Fried potatoe </2>
	</favorite_food>
	<favorite_season> 
		<1> Summer </1>
		<2> Autumn </2>
	</favorite_season> 
	<favorite_countries>
		<1> Switzerland <1/>
		<2> Canada </2>
	<favorite_countries>
</preference>
```

11.Create a skills.xml file, add information about the skills that will be studied in the course in XML format - `touch skills.xml`:

```
<?xml version="1.0" encoding="UTF-8"?>
<skills>
	<1> Basic theory </1>
	<2> What is client-server architecture </2>
	<3> HTTP Server request methods </3>
	<4> HTTP server response codes </4>
	<5> HTTP request and response structures </5>
	<6> What is JSON, XML. Their structure </6>
	<7> API testing via Postman (JS, API autotests) </7>
	<8> Removing and reading logs from an external server </8>
	<9> Sniffing http web traffic via Charles and Fiddler </9>
 	<10> Dev Tools of web browsers (Google Chrome, FireFox) </10>
	<11> VPN. (How it works, why you need it, how to use it, tool options) </11>
	<12> Mobile testing </12>
	<13> iOS feature, android, guidelines </13>
	<14> Building iOS apps with XCode </14>
	<15> Building Android apps with Android Studio </15>
	<16> ADB (android device management) </16>
	<17> Proxy and vpn setup on iOS and Android </17>
	<18> Interception (sniffing) mobile traffic via Charles and Fiddler on iOS and Android </18>
	<19> Linux command line (terminal) (copy, create, view, move files on non-GUI servers) </19>
	<20> Basic bash scripting, automation of routine tasks on the server </20>
	<21> Access to remote servers </21>
	<22> SQL Basics (Create, Delete, Drop, Insert Into, Select, From, Where, Join) </22>
	<23> Postgres database (installation, configuration and use) </23>
	<24> Redis non-relational database (installation, configuration and use) </24>
	<25> Load testing in Jmeter </25>
	<26> Scrum development methodology </26>
</skills>
```

12. Make a commit in one line - `git add . && git commit -m "2 new files"`;

13. Send 2 files at once to an external repository - git push;

14. On the web interface, create the bug_report.xml file;

15. Make Commit changes (save) changes on the web interface;

16. Modify the bug_report.xml file on the web interface, add a bug report in XML format:

```
<?xml version="1.0" encoding="UTF-8"?>
<bug_report>
  <project> Notes </project>
  <version> 1.3 </version>
  <id> №5 </id>
  <summary> When clicking on the 'A to Z' filtering button on the main page of the application, chaotic filtering of lists occurs </summary>
  <step_to_reproduce>
    <1> 1. Open the 'Notes' app </1>
    <2> 2. Create 15 lists that will start accordingly (A, a, D, 3, :, U, u, Ш, ш, 5, @, Ї, ї, -, d) </2>
    <3> 3. On the main page of the application, click on the filter button 'A to Z' </3>
  </step_to_reproduce>
  <actual_result> Lists are sorted randomly </actual_result>
  <expected_result>  
    <1> The lists are sorted in order: symbols, numbers, Latin letters (upper case first), Cyrillic letters (upper case first) </1>
    <2> Correct order : (-, :, @, 3, 5, А, а, D, d, U, u, Ї, ї, Ш, ш) </2>
  </expected_result>
  <severity> Minor </severity>
  <priority> Normal </priority>
  <status> New </status>
  <environment> IPhone 7 Plus, version 15.4.1 </environment>
  <author> Vitaly </author>
  <assignee> Ivan </assignee>
</bug_report>
```

17. Make Commit changes (save) changes on the web interface;

18. Synchronize external and local XML repository - `git pull`.