# 1. Create Project Structure

a) Create a new workspace in Eclipse IDE
> ![image](https://user-images.githubusercontent.com/120084864/207497789-0375e36d-43b6-46d2-93f1-3cc3b669a571.png)

b) Create a new Maven Project
> File > New > Project
> ![image](https://user-images.githubusercontent.com/120084864/207498000-4d76c6a2-82c9-4aac-8c1d-49c828e2f249.png)
> ![image](https://user-images.githubusercontent.com/120084864/207498500-ec46404a-30f1-44e3-9d54-e5c6325f83f7.png)
> ![image](https://user-images.githubusercontent.com/120084864/207498944-eabc7e96-9931-4bb2-993d-70409ace2360.png)
> ![image](https://user-images.githubusercontent.com/120084864/207499148-730a5934-15f1-4fec-a89f-e0d36e3ff409.png)

> final output
>> ![image](https://user-images.githubusercontent.com/120084864/207501150-44f8addb-345c-4dfe-8c4b-95b0e5bc049f.png)

c) Configure Maven Dependency in pom.xml

Dependencies used :
> 1. Selenium Java 

<!-- https://mvnrepository.com/artifact/org.seleniumhq.selenium/selenium-java -->
		<dependency>
			<groupId>org.seleniumhq.selenium</groupId>
			<artifactId>selenium-java</artifactId>
			<version>4.7.1</version>
		</dependency>

> 2. TestNG

<!-- https://mvnrepository.com/artifact/org.testng/testng -->
		<dependency>
			<groupId>org.testng</groupId>
			<artifactId>testng</artifactId>
			<version>7.7.0</version>
			<scope>test</scope>
		</dependency>

> 3. ReportNG

<!-- https://mvnrepository.com/artifact/org.uncommons/reportng -->
		<dependency>
			<groupId>org.uncommons</groupId>
			<artifactId>reportng</artifactId>
			<version>1.1.4</version>
			<scope>test</scope>
		</dependency>
    
> 4. Log4j-core and Log4j-api

<!-- https://mvnrepository.com/artifact/org.apache.logging.log4j/log4j-core -->
		<dependency>
			<groupId>org.apache.logging.log4j</groupId>
			<artifactId>log4j-core</artifactId>
			<version>2.19.0</version>
		</dependency>
		<!-- https://mvnrepository.com/artifact/org.apache.logging.log4j/log4j-api -->
		<dependency>
			<groupId>org.apache.logging.log4j</groupId>
			<artifactId>log4j-api</artifactId>
			<version>2.19.0</version>
		</dependency>
    
> 5. Apache POI

<!-- https://mvnrepository.com/artifact/org.apache.poi/poi -->
		<dependency>
			<groupId>org.apache.poi</groupId>
			<artifactId>poi</artifactId>
			<version>5.2.3</version>
		</dependency>
    
> 6. WebDriverManager

<!-- https://mvnrepository.com/artifact/io.github.bonigarcia/webdrivermanager -->
		<dependency>
			<groupId>io.github.bonigarcia</groupId>
			<artifactId>webdrivermanager</artifactId>
			<version>5.3.1</version>
		</dependency>
    
Copy and paste all this in pom.xml

> final ouput
![image](https://user-images.githubusercontent.com/120084864/207502950-134c282b-45fb-41e0-9489-bd1f26e10e6c.png)

d) Create basic packages in `test/java` and `test/resources`

In `test/java` must provide :

1. base
2. testcase
3. utilities

In `test/resources` must provide :

1. configfiles
2. logs
3. reports
4. testdata

>![image](https://user-images.githubusercontent.com/120084864/207503532-9caa9e35-6d60-4d95-9088-f8abcc7db36e.png)







