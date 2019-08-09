# Entity Framework Code First Sample For absolute Beginners

# Steps 

1- create console application 
2- install Entity frame work from package manager consol 
	```
	install-package EntityFramwork
	```
3- add your domain classes with realtions
4- add your model context and DBSets for your domain classes
5- add the connection string and attach providerName = "System.Data.SqlCleint" add the end of it
	the name for connection string can be the same name of context class name 
	or you can change it and add  : base("name=(namehere)") after the class defination
6- from package manager console enable , add migrationa  and update database
	```
	-  enable-migrations
	-  add-migration InitialModel
	-  update-database
	```
	