# SOAPUI
1,. Download SOAPUI Open source

2. Go to create project>New rest project 
3. Enter the Sample rest url: http://petstore.swagger.io/v2/swagger.json
4. Click ok button

![image](https://user-images.githubusercontent.com/43099966/109734295-110e8180-7bc1-11eb-9fd2-b0362c8994f1.png)

Select json format to view response

5. Go ahead to add testca by right clicking on request 1 menu

![image](https://user-images.githubusercontent.com/43099966/109734619-95f99b00-7bc1-11eb-9ec5-d2edebbab675.png)



DownloaD SOAUI PRO/ready API
CREATE WORKSPACE
create new soap project>Enter the path of the WSDL request. In this case http://www.dneonline.com/calculator.asmx?wsdl

![image](https://user-images.githubusercontent.com/43099966/109778788-856b1400-7c05-11eb-95c6-2b530577cbbf.png)

Click ok

You can see this screen as there are two operations imported into the project

![image](https://user-images.githubusercontent.com/43099966/109779062-daa72580-7c05-11eb-8161-61364135350d.png)

Right click on Add and click on new request

![image](https://user-images.githubusercontent.com/43099966/109779242-0aeec400-7c06-11eb-8021-6b699bbaf854.png)

Enter init A and init B

![image](https://user-images.githubusercontent.com/43099966/109779595-63be5c80-7c06-11eb-99a9-43ea7cc1bd9b.png)

Then submit

You c an see the result

![image](https://user-images.githubusercontent.com/43099966/109779854-ab44e880-7c06-11eb-907b-0200372389d0.png)


Then you can go ahead and create test suite in a situation , you want to have different comination

creating new test suite: Go to project>create new test suite
then create new testcase 'Add'

![image](https://user-images.githubusercontent.com/43099966/109780906-b8aea280-7c07-11eb-84f8-a989208784f4.png)
There three property one  test step for functional, load / performance and security

![image](https://user-images.githubusercontent.com/43099966/109781061-e1369c80-7c07-11eb-950d-0291f84561c5.png)

Go ahead and add teststp >soap request>Add

![image](https://user-images.githubusercontent.com/43099966/109781987-af720580-7c08-11eb-87b0-516ee0133229.png)

Observe the Add request xml request for call request and response request

![image](https://user-images.githubusercontent.com/43099966/109782471-3aeb9680-7c09-11eb-83ff-d86347eea7b0.png)

Observe the Add request raw request for call request and response request

![image](https://user-images.githubusercontent.com/43099966/109782800-93229880-7c09-11eb-960a-542f72d66b5a.png)

# Assertions

Assertion are checkpoint or validation point to confirm the state of something
'The following are the assertion availaible in open source
Property Content
Compliance Status Standard
Script
SLA
JMS
Security
 In this study , these are the assertions we will take a look at
 
 Contains Assertion
 
 step1:To add assertion click on assertion menu 
 
 ![image](https://user-images.githubusercontent.com/43099966/109783834-b6017c80-7c0a-11eb-9482-28b33a10559d.png)
 
 step2:Select the Assertion Category.
Select the Assertion Type.
Click 'Add'

![image](https://user-images.githubusercontent.com/43099966/109784270-30ca9780-7c0b-11eb-9828-891ac2ec5115.png)

You can assert or  validate if the string '46' exist in the response.

You can assert or  validate if the string '47' exist in the response.

![image](https://user-images.githubusercontent.com/43099966/109784833-c49c6380-7c0b-11eb-8577-007a51642713.png)


Not contains Assertion
X Path Match Assertion.
![image](https://user-images.githubusercontent.com/43099966/109797358-a6d5fb00-7c19-11eb-9eb4-83a17ff98dce.png)
And click on save
Scripting Assertion
X Query Match Assertion






