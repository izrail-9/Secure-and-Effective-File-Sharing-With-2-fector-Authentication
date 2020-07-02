INTRODUCTION
Introduction
Cloud computing could also be a virtual host computer system that allows enterprises to buy for, lease, sell, or distribute software and other digital resources over the online as an on-demand service. It not depends on a server or sort of machines that physically exist, because it's going to be a virtual system. There are many applications of cloud computing, like data sharing data storage, big data management medical information system etc. the advantages of web-based cloud computing services are huge, which include the convenience of accessibility, reduced costs and capital expenditures, increased operational efficiencies, scalability, flexibility and immediate time to plug. This project concerning of both privacy and security for web-based cloud services. As sensitive data could even be stored within the cloud for sharing purpose or convenient access; and eligible users also can access the cloud system for various applications and services. A user is required to login before using the cloud services or accessing the sensitive data stored within the cloud. First, the traditional account/password-based authentication isn't privacy-preserving. However, it's well acknowledged that privacy is an important feature which must be considered here within the cloud computing systems. Second, it's normal to share a computer among different people. There could also be change to hack the login password using some spyware. A recently proposed access control model called attribute-based access control could also be an honest candidate to tackle the first problem. It not only provides anonymous authentication but also further defines access control policies supported different attributes of the requester, environment, or the info object. In an attribute-based access system, each user features a user secret key issued by the authority. In practice, the user secret key's stored inside the private computer. once we consider the above mentioned second problem on web-based services, it's common that computers could also be shared by many users especially in some large enterprises or organizations. for instance, allow us to consider the subsequent two scenarios: • during a hospital, computers are shared by different staff. Dr. Henry uses the pc in room A when she is on duty within the daytime, while Dr. Mark uses an equivalent computer within the same room when he's on duty in the dark. • during a university, computers within the undergraduate lab are usually shared by different students. In these cases, user secret keys could be easily stolen or employed by an unauthorized party. albeit the pc could even be locked by a password, it can still be possibly guessed or stolen by undetected malwares. A safer way is to use two-factor authentication (2FA). 2FA is employed for web-based e-banking services. additionally, to a username/password, the user is additionally required to possess a tool to display a onetime password. Some systems may require the user to possess a mobile while the one-time password is getting to be sent to the mobile through SMS during the login process. For the same reason, it'll be better to possess a 2FA system for users within the web-based cloud services so on extend the security level within the system.












ABSTRACT
	In this Project, we introduce a new ‘Secure and Effective File Sharing with two factor Authentication’ for web-based cloud computing services. In our proposed system we are implementing two factor authentication such as both secret key and trustee acceptance certificate As a user cannot access the system if they do not hold both, the mechanism can enhance the safety of the system, especially in those re scenarios where many users share an equivalent computer for web-based cloud services. Here we are adding cloud to upload the encrypted files for security, i.e., the cloud server only knows that the user fulfills the required predicate, but has no idea on the exact identity of the user. At last, we also perform or practically to access the file using two factor Authentication.











SYSTEM STUDY

FEASIBILITY STUDY

          The feasibility study of the project is used for the analyzing the detailed structure of the project and cost estimation. During system analysis the feasibility study of the proposed system is to be applied. this could be to substantiate that the proposed system isn't a burden to the company.  For feasibility analysis, some understanding of the most requirements for the system is vital.

Three key considerations involved within the feasibility analysis are	

•ECONOMICAL FEASIBILITY
•TECHNICAL FEASIBILITY
•SOCIAL FEASIBILITY
ECONOMICAL FEASIBILITY
  This study is run to check the economic impact that the system will wear the organization. the amount of fund that the company can pour into the research and development of the system is restricted. The expenditures must be justified. Thus the developed system also within the budget and this was achieved because most of the technologies used are freely available. Only the customized products had to be purchased. 

TECHNICAL FEASIBILITY
                
   This study is run to check the technical feasibility, that is, the technical requirements of the system. there was a high demand on all the available technical resources this might lead to high demands on the available technical resources. this might lead to high demands being placed on the client. There was a minimal or null change are required to implement the system.
SOCIAL FEASIBILITY
The aspect of study is to test the extent of acceptance of the system by the user. This includes the method of coaching the user to use the system efficiently. the extent of acceptance by the users solely depends on the methods that are employed to teach the user about the system and to create him conversant in it. His level of confidence must be raised so he's also able to make some constructive criticism, which is welcomed, as he's the ultimate user of the system.





                                            


SOFTWARE ENVIRONMENT

HTML  
Hypertext Markup language (HTML) is the standard Markup language for creating web pages and web applications. With Cascading Style Sheets (CSS) and JavaScript, it forms a triad of cornerstone technologies for the World Wide Web. 
Web browsers receive HTML documents from a web server or from local storage and render the documents into multimedia web pages. HTML describes the structure of a web page semantically and originally included cues for the appearance of the document. 
•	HTML describes the structure of Web pages using Markup
•	HTML elements are the building blocks of HTML pages
•	HTML elements are represented by tags
•	HTML tags label pieces of content such as "heading", "paragraph", "table", and so on
•	Browsers do not display the HTML tags, but use them to render the content of the page.
CSS
CSS is used to control the style of a web document in a simple and easy way. CSS is the acronym for "Cascading Style Sheet". Cascading Style Sheets, fondly referred to as CSS, is a simple design language intended to simplify the process of making web pages presentable.
Advantages of CSS: 
•	CSS saves time − You can write CSS once and then reuse same sheet in multiple HTML pages. You can define a style for each HTML element and apply it to as many Web pages as you want.
•	Pages load faster − If you are using CSS, you do not need to write HTML tag attributes every time. Just write one CSS rule of a tag and apply it to all the occurrences of that tag. So less code means faster download times.
•	Easy maintenance − To make a global change, simply change the style, and all elements in all the web pages will be updated automatically.
•	Superior styles to HTML − CSS have a much wider array of attributes than HTML, so you can give a far better look to your HTML page in comparison to HTML attributes.
•	Multiple Device Compatibility − Style sheets allow content to be optimized for more than one type of device. By using the same HTML document, different versions of a website can be presented for handheld devices such as PDAs and cell phones or for printing.
•	Global web standards − Now HTML attributes are being deprecated and it is being recommended to use CSS. So its a good idea to start using CSS in all the HTML pages to make them compatible to future browsers.
Bootstrap 4
Bootstrap is an open source framework used to develop the responsive web applications or responsive designs. Responsive means application should be runs on smaller screens like mobile phones and tablets. Every element of the HTML document gets stacked when the page gets smaller or minimized. By default, bootstrap takes 12 columns of width with equal separation of the columns that means every column having same size. But you can alter the default values and you can make layouts, design
according to your requirements using <span> tag.
 
Bootstrap provide grid system for all kind of devices such as extra small, small, medium, large, extra-large which can help to run the app on every device. Further it provides some stylish buttons, forms, tables and so on. Bootstrap 4 is the newest version with some additional features compare to previous versions. In this project bootstrap 4 is used for the front development along with the Django framework.
Data Analytics
Data analytics is the science of analyzing raw data in order to make conclusions about that information. Many of the techniques and processes of data analytics have been automated into mechanical processes and algorithms that work over raw data for human consumption.
Data analytics techniques can reveal trends and metrics that would otherwise be lost in the mass of information. This information can then be used to optimize processes to increase the overall efficiency of a business or system.
Data analytics is broken down into four basic types.
•	Descriptive analytics describes what has happened over a given period of time. Have the number of views gone up? Are sales stronger this month than last?
•	Diagnostic analytics focuses more on why something happened. This involves more diverse data inputs and a bit of hypothesizing. Did the weather affect beer sales? Did that latest marketing campaign impact sales?
•	Predictive analytics moves to what is likely going to happen in the near term. What happened to sales the last time we had a hot summer? How many weather models predict a hot summer this year?
•	Prescriptive analytics suggests a course of action. If the likelihood of a hot summer is measured as an average of these five weather models is above 58%, we should add an evening shift to the brewery and rent an additional tank to increase output.
Django
Django is an open source and web framework present in python which is developed and maintain by DSF (Django Software Foundation). Now a days Django widely in used because of its more built in functionalities. There are some famous and well-known companies and apps are using Django for the development of their websites and those companies and apps are Google, Instagram, Discus, Spotify, You Tube, Pinterest, it is used in web development in python. It support templates and static files that means you can easily render the HTML pages by putting all the HTML files in the directory called ‘templates’ and similarly you can place all the files related to styles like CSS and JS will be placed inside the directory called ‘static’. In this project Django is used for the frontend development. Further Django provide more features as compared to other frameworks and those features are given below.
1.	Built in localhost server
2.	Built in administration facility
3.	High security
4.	Rapid development
5.	Outstanding documentation
Bootstrap 4
Bootstrap is an open source framework used to develop the responsive web applications or responsive designs. Responsive means application should be runs on smaller screens like mobile phones and tablets. Every element of the HTML document gets stacked when the page gets smaller or minimized. By default, bootstrap takes 12 columns of width with equal separation of the columns that means every column having same size. But you can alter the default values and you can make layouts, design
according to your requirements using <span> tag.
 
Bootstrap provide grid system for all kind of devices such as extra small, small, medium, large, extra-large which can help to run the app on every device. Further it provides some stylish buttons, forms, tables and so on. Bootstrap 4 is the newest version with some additional features compare to previous versions. In this project bootstrap 4 is used for the front development along with the Django framework.
Installing Anaconda Python, Spyder and Jupyter Notebook
Navigate to Spyder’s website and find the installer.
It’s recommended that you install the Anaconda distribution to get Spyder; this distribution contains some useful packages and an environment manager to keep your packages installed and up to date.
Select Download from the main menu, and then click on the Download Spyder with Anaconda button.
 
This will take you to a screen where you select your operating system for the installation. Click on the Windows icon.
 
You’ll be asked whether you’d like to download Python 3 or Python 2. We’ll go with the latest version of Python (which, as of this writing, is Python 3.7).
 
Once the installer has downloaded and you run it, the Setup window will display.
 
Click the Next button. In the License Agreement window, you’ll need to accept the terms by clicking the I Agree button.
 
Click Next to proceed through the rest of the windows.
 
 
Once you reach the page below, click the Install button.
 
The installation process will begin.
 
 
You can download Visual Studio Code if you’d like to use it. It’s a versatile IDE for developing in a variety of programming languages. We won’t install it in this article, though. Click the Skip button.
 
Once the installation is complete, click the Finish button.
 
Afterwards, go to Start › All programs (this is if you’re on Windows 7—if you’re on Windows 10, press the Windows key and look under Recently added). Select Anaconda Navigator.
You should see a window similar to the one below:
 
If you’d like run Spyder, just click on its Launch button. The IDE will open.
 

Installing Visual Studio Code

Visual Studio Code
                     Visual Studio Code is a lightweight but powerful source code editor which runs on your desktop and is available for Windows, macOS and Linux. It comes with built-in support for JavaScript, TypeScript and Node.js and has a rich ecosystem of extensions for other languages (such as C++, C#, Java, Python, PHP, Go) and runtimes (such as .NET and Unity).  
Installed Studio Code
•	Click-> Windows and Download
 
•	Downloaded
 
•	Ready to installing

 
•	Setup is Installed
 
Click on the Extension and Search Python and Install the PYTHON











SYSTEM ANALYSIS
EXISTING SYSTEM:
	•Mediated cryptography was first introduced as the simplest way to allow immediate revocation of public keys. the essential idea of mediated cryptography is to use an on-line mediator for each transaction. This on-line mediator is mentioned a SEM (Security Mediator) since it provides an impact of security capabilities. If the SEM doesn't cooperate then no transactions with the public key are possible from now on .
	•The general idea of key-insulated security was to store long-term keys during a physically-secure but computationally-limited device. Secret key should be stored for Short-term on a strong. Short term secrets are then refreshed at discrete time periods via interaction between the user and thus the underside while the public key remains unchanged throughout the lifetime of the system.
DISADVANTAGES OF EXISTING SYSTEM:
•Key-insulated crypto system requires all users to update their keys in on every occasion period. The key update process requires the safety device.
•Once the key has been updated, the signing or decryption algorithm doesn't require the device anymore within the same period of your time.
•The traditional account/password-based authentication isn't privacy preserving. However, it's well acknowledged that privacy is a crucial feature that possesses to be considered in cloud computing systems.
•The same computers are shared among different people. it's going to be easy for hackers to place in some spyware to seek out out the login password from the web-browser.
•Access without Secret Key: The adversary tries to access the system; within its privileges; with none secret key. It can have its own security device.
PROPOSED SYSTEM:
••In this project, we are implementing two-factor access system for web-based cloud computing services, by providing secret key and trustee issued certificate. If user holds both the items then only, they will access the file
•Using Trustee Certificate, our System will provide a 2FA security. First the user secret key (which is usually stored inside the computer) is required additionally the trustee issued certificate. The user is often granted access as long as he has both items.
•Since the user cannot use his secret key and trustee issued certificate to access the system. Our Application supports two factor authentications for file to allow the user to access the files. At the identical time, the privacy of the user is additionally preserved. The cloud system only knows that the user possesses some required attribute, but not the important identity of the user.
ADVANTAGES OF PROPOSED SYSTEM:
	•Our protocol supports attribute-based access which provides a great flexibility for the system to set different access policies according to different scenarios. At an equivalent time, the privacy of the user is additionally preserved. The cloud system only knows that the user possesses some required attribute, but not the important identity of the user.
	•To show the practicality of our system, we simulate the prototype of the protocol.
	•Tamper-resistance. The content stored inside the security device is not accessible nor modifiable once it is initialized. In addition, it'll always follow the algorithm specification.
	•It is capable of evaluation of a hash function. In addition, it can generate random numbers and compute exponentiations of a cyclic group defined over a finite field.
	•Presented a new 2FA (including both user secret key and a lightweight security device) access control system for web-based cloud computing services.
	•2FA access control system has been identified to not only enable the cloud server to restrict the access to those users with the same set of attributes but also preserve user privacy.


















SYSTEM DESIGN
SYSTEM ARCHITECTURE:


 










DATA FLOW DIAGRAM:

1.	The DFD is also called as bubble chart. It is a simple graphical formalism that can be used to represent a system in terms of input data to the system, various processing carried out on this data, and the output data is generated by this system.
2.	The data flow diagram (DFD) is one of the most important modeling tools. It is used to model the system components. These components are the system process, the data used by the process, an external entity that interacts with the system and the information flows in the system.
3.	DFD shows how the information moves through the system and how it is modified by a series of transformations. It is a graphical technique that depicts information flow and the transformations that are applied as data moves from input to output.
4.	DFD is also known as bubble chart. A DFD may be used to represent a system at any level of abstraction. DFD may be partitioned into levels that represent increasing information flow and functional detail.














aaa


















UML DIAGRAMS

UML stands for Unified Modeling Language. UML is a standardized general-purpose modeling language in the field of object-oriented software engineering. The standard is managed, and was created by, the Object Management Group. 
The goal is for UML to become a common language for creating models of object-oriented computer software. In its current form UML is comprised of two major components: a Meta-model and a notation. In the future, some form of method or process may also be added to; or associated with, UML.
	The Unified Modeling Language is a standard language for specifying, Visualization, Constructing and documenting the artifacts of software system, as well as for business modeling and other non-software systems. 
The UML represents a collection of best engineering practices that have proven successful in the modeling of large and complex systems.
 The UML is a very important part of developing objects-oriented software and the software development process. The UML uses mostly graphical notations to express the design of software projects.

GOALS:
	The Primary goals in the design of the UML are as follows:
1.	Provide users a ready-to-use, expressive visual modeling Language so that they can develop and exchange meaningful models.
2.	Provide extendibility and specialization mechanisms to extend the core concepts.
3.	Be independent of particular programming languages and development process.
4.	Provide a formal basis for understanding the modeling language.
5.	Encourage the growth of OO tools market.
6.	Support higher level development concepts such as collaborations, frameworks, patterns and components.
7.	Integrate best practices.
8.	


USE CASE DIAGRAM:
A use case diagram in the Unified Modeling Language (UML) is a type of behavioral diagram defined by and created from a Use-case analysis. Its purpose is to present a graphical overview of the functionality provided by a system in terms of actors, their goals (represented as use cases), and any dependencies between those use cases. The main purpose of a use case diagram is to show what system functions are performed for which actor. Roles of the actors in the system can be depicted.



































CLASS DIAGRAM:
In software engineering, a class diagram in the Unified Modeling Language (UML) is a type of static structure diagram that describes the structure of a system by showing the system's classes, their attributes, operations (or methods), and the relationships among the classes. It explains which class contains information.




















SEQUENCE DIAGRAM:
A sequence diagram in Unified Modeling Language (UML) is a kind of interaction diagram that shows how processes operate with one another and in what order. It is a construct of a Message Sequence Chart. Sequence diagrams are sometimes called event diagrams, event scenarios, and timing diagrams










































ACTIVITY DIAGRAM:
Activity diagrams are graphical representations of workflows of stepwise activities and actions with support for choice, iteration and concurrency. In the Unified Modeling Language, activity diagrams can be used to describe the business and operational step-by-step workflows of components in a system. An activity diagram shows the overall flow of control.

































SYSTEM REQUIREMENTS:
HARDWARE REQUIREMENTS:

•	System		: HP Laptop.
•	Hard Disk        	: 4GB. 
•	Floppy Drive	: 1.44 Mb.
•	Monitor		: 15 VGA Colour.
•	Mouse		: Logitech.
•	Ram			: 512 Mb.

SOFTWARE REQUIREMENTS:

•	Operating system 	: - Windows 10.
•	Coding Language	:  PYTHON/DJANGO
•	Data Base		:  PostgreSQL








SYSTEM TESTING
The purpose of testing is to induce errors. Testing is that the method of trying to induce every conceivable fault or weakness in a very work product. The testing is mainly used to find whether the user requirements has satisfied or not that in any situation Software system doesn’t fail in any unacceptable manner. There are various sorts of test. Each test type addresses a particular testing requirement.
TYPES OF TESTS
Unit testing
Unit testing involves the planning of test cases that validate that the inner program logic is functioning properly, which program inputs produce valid outputs. we are validating all the decision branches and internal code. it's the individual software units of the appliance and after the completion of personal unit before integration. this can be a structural testing, that relies on knowledge of its construction and is invasive. Unit tests perform basic tests at component level and test a selected business process, application, and/or system configuration. This Unit tests make sure that each unique path of a business process should performs accurately to the documented work and it contains proper defined inputs and expected outcomes.
Integration testing
Integration tests are designed to check integrated software components to work out if they really run united program.  Testing is event driven and is more concerned with the essential outcome of screens or fields. If the unit testing has to be successfully done then the Integration tests demonstrate that although the components were individually satisfaction, as shown by successfully unit testing, the mixture of components is correct and consistent. Integration testing is specifically aimed toward   exposing the issues that arise from the mixture of components.
Functional test
Functional tests provide systematic demonstrations that functions tested are specified by the business and technical requirements, system document, and user manuals.
Functional testing is centered on the subsequent items:
Valid Input               :  identified classes of valid input must be accepted.
Invalid Input             : identified classes of invalid input must be rejected.
Functions                  : identified functions must be exercised.
Output           	   : identified classes of application outputs must be exercised.
Systems/Procedures: interfacing systems or procedures must be invoked.

     Organization and preparation of functional tests is targeting requirements, key functions, or special test cases. additionally, systematic coverage regarding identify Business process flows; data fields, predefined processes, and succe Methodologies
User Module
The user can able to register their own account and they can able to login the application using their own credentials and if they logged in also they can’t able to access the application because the user will receive the OTP in their registered Email id. If that OTP matches then the user can able to access the system.
Authority Module
The Authority is a authorized person to access this entire application and admin has access the application by login their account and admin only the authorized person to upload the files and admin can able to view all the user details and the file request from user
Trustee Module
The Trustee is the person who will give access to the user download the file and they can able to view all the user and request from the user
Secret Key Generation
Admin will generate unique secret key for all the files uploaded by him..if the user request the file the admin will send the secret key to the user email.

essive processes must be considered for testing. Before functional testing is complete, additional tests are identified and thus the effective value of current tests is about.
System Test
     System testing ensures that the whole integrated computer code meets requirements. It tests a configuration to confirm known and predictable results. An example of system testing is that the configuration oriented system integration test. System testing relies on process descriptions and flows, emphasizing pre-driven process links and integration points.
White Box Testing
White Box Testing could be a testing within which within which the software tester has knowledge of the inner workings, structure and language of the software, or a minimum of its purpose. it's purpose. it's accustomed test areas that can't be reached from a recording machine level.
Black Box Testing
Black Box Testing is testing the software with none knowledge of the inner workings, structure or language of the module being tested. recorder tests, as most different kinds of tests, must be written from a definitive source document, like specification or requirements document, like specification or requirements document. it's a testing during which the software under test is treated, as a recorder .you cannot “see” into it. 
Unit Testing:
	Unit testing is usually conducted as part of a combined code and unit test phase of the software lifecycle, although it is not uncommon for coding and unit testing to be conducted as two distinct phases.
Test strategy and approach
	Field testing will be performed manually and functional tests will be written in detail.

Test objectives
•	All field entries must work properly.
•	Pages must be activated from the identified link.
•	The entry screen, messages and responses must not be delayed.

Features to be tested
•	Verify that the entries are of the correct format
•	No duplicate entries should be allowed
•	All links should take the user to the correct page.
Integration Testing
	Software integration testing is the incremental integration testing of two or more integrated software components on a single platform to produce failures caused by interface defects.
	The task of the integration test is to check that components or software applications, e.g. components in a software system or – one step up – software applications at the company level – interact without error.
Test Results: All the test cases mentioned above passed successfully. No defects encountered.
Acceptance Testing
	User Acceptance Testing is a critical phase of any project and requires significant participation by the end user. It also ensures that the system meets the functional requirements.
Test Results: All the test cases mentioned above passed successfully. No defects encountered.










INPUT DESIGN AND OUTPUT DESIGN
INPUT DESIGN
The input design is that the link between the knowledge system and therefore the user. It comprises the developing specification and procedures for data preparation and people steps are necessary to place transaction data in to a usable form for processing are often achieved by inspecting the pc to read data from a written or printed document or it can occur by having people keying the info directly into the system. the planning of input focuses on controlling the quantity of input required, controlling the errors, avoiding delay, avoiding extra steps and keeping the method simple. The input is meant in such how in order that it provides security and simple use with retaining the privacy. Input Design considered the subsequent things:
	What data should tend as input?
	 How the information should be found?
	 Guide the operating professional to put the inputs.
	To prepare input validation and found errors in the code.
OBJECTIVES
1.The process of converting user-oriented description of the input into computer based is called as input design
This design plays vital role to avoid errors within the data input process and displays the right way for obtaining correct information form the computerized system
2. it's achieved by creating user-friendly screens for the info entry to handle large volume of knowledge. The goal of designing input is to form data entry easier and to be free from errors. the info entry screen is meant in such how that each one the info manipulates are often performed. It also provides record viewing facilities.
3. When the info is entered it'll check for its validity. Data are often entered with the assistance of screens. Appropriate messages are provided as when needed in order that the user won't be in maize of instant. Thus, the target of input design is to make an input layout that's easy to follow
OUTPUT DESIGN
A quality output is one, which meets the wants of the top user and presents the knowledge clearly. In all the system the results should be communicated to the users and to other system through outputs. In output design it's determined how the knowledge is to be displaced for immediate need and also the text output. It is the foremost important and direct source information to the user. Efficient and intelligent output design improves the system’s relationship to assist user decision-making.
1. All the output should be proceeding in an organized, and well mannered; the output should be proper in order that people can use easily and effectively. When analysis design computer output, they ought to Identify the precise output that's needed to satisfy the wants.
2. Select methods for presenting information.
3. Creating all the documents, report or any other formats which contains information produced by the system 
The output sort of a data system should accomplish one or more of the subsequent objectives.
	There must be information about past, present and future activities.
	Signal important events, opportunities, problems, or warnings.
	Trigger an action.
	Confirm an action.
















LITERATURE SURVEY

 	There was such an oversized amount of information centers in numerous different locations to share the web over all the patrons through cloud computing resources.
it's totally difficult to predict geographic distribution of users to consume their resources over the Could computing Providers, hence the load coordination must happen automatically, the goal is to make a computing environment that supports dynamic expansion or contraction of capabilities using the Cladism toolkit The results demonstrate that federated Cloud computing model has immense potential because it offers significant performance gains as regards to latency and value saving under dynamic workload scenarios.
There is a rise in scale and complexity to represent workload benchmarks to evaluate the performance effects of the system charges. The goal is to hunt out an accurate characterization which can faithfully reproduce the performance of historical workload traces in terms of key performance metrics Through experiments using workload The synthetic workload traces accurately recycling of the resources and waiting time for every tasks which needs to be traces from Google production clusters.
Data intensive applications in cloud computing environment are using MapReduce for processing. The cloud service Providers (CSP) are using this data to arrange better scheduling decision and that we use an instance-based learning technique that used temporal locality to predict job completion times from all the data and using the dataset
Apache Hadoop, is increasingly getting used for data intensive applications in cloud computing environments. MapReduce environments benefits both the cloud 
service providers and their users. metrics and job configuration features like 
format of the input/output files, style of compression used etc. to search out similarity among Hadoop jobs
















Future Work
Detailed security analysis shows that the proposed 2FA access system achieves the specified security requirements. Through performance evaluation, we demonstrated that the development is possible. We leave as future work to further improve the efficiency while keeping all nice features of the system and that we will give more security to files like finger print matching and to enhance the trust worthiness of the files













PROGRAM CODE
USER HOMEPAGE:
 
USER LOGIN:
 

SETTING.PY:
 
MAIN APP URL.PY:
 
USER REGISTRATION CODE:
 
USER LOGIN.PY:
 
TERUSTEE HOMEPAGE CODE:
 
OTP CODE:
 

USER REQUEST CODE:
 
USER NOTIFICATION CODE
 
PROJECT SCREENSHOT
 HOMEPAGE:
 
USER REGISTRATION:
 
USER LOGIN:
 
USER HOMEPAGE:
 


IF USER ALREADY TAKEN:
 
USERNAME AND PASSWORD ARE NOT MATCHED:
 


USER OTP NOTIFICATION:
 
CHANGE PASSWORD
 

USER REQUEST PAGE

 


USER REQUEST FOR FILE:
 
TRUSTEE LOGIN:
 
TRUSTEE HOMEPAGE:
 
TRUSTEE UPLOAD FILE:
  
USER RQUESTPAGE
 
USER FILE ALLOWED BY TRUSTEE:
 
TRUSTEE GIVEN THE PERMISSION TO USER:
  

AUTHORITY HOMEPAGE:
 
AUTHORITY GIVE THE PERMISSION:
 

PENDING REQUEST BY AUTHORITY:
 

AUTHORITY GIVEN THE PERMISSION:
 

USER DOWNLOAD THE FILE 
DJANGO ADMINISTRATION:
 

DJANGO HOMEPAGE:
 
HOME ADMINISTRATION:
 

CUSTOM USER NAME:
 


CHANGE REQUEST:
 
ALL FILES UPLOAD BY TRUSTEE AND ADMIN:
 
REQUEST PAGE:
 

OUR TEAM:
 
ADD CONNECT ADMIN:
 


GROUPS:
 
USER LOG_APP:
 


CONCLUSION
In this system, propose a replacement technique of maintaining the policy attributes separately in such how that the worker call any time update / add new policy for existing encrypted document. Therefore, our system is reduced compilation time. The advantage of this technique is employed two factor authentication Factor for File Sharing. This paper shows security of document on cloud server with the assistance of advanced ABE techniques. For future work by using this technique, attempt to give security of both time-sensitive data and fine-gained access control.











REFERENCES
[1] Nilghai Yu and Pelini Hong, “TAFC: Time and Attribute Factors Combined Access Control for Time-Sensitive Data in Public Cloud” IEEE Transactions on Services Computing available online,2017. 
[2] H. Tian, Y. Chen,C.-C. Chang, H. Jiang, Y. Huang,Y. Chen, and J. Liu, “Dynamic-hash-table based publicauditing for secure cloud storage,” IEEE Transactions on Services Computing,Avaliable online, 2016. 
[3] C. Wang, Q. Wang, K. Ren, N. Cao, and W. Lou, “Toward secure and dependable storage services in cloud computing,” IEEE Transactions on Services Computing, vol. 5, no. 2, pp. 220–232, 2012. 
[4] K. Yuan, Z. Liu, C. Jia, J. Yang, and S. Lv, “Public key timed-release searchable encryption,” in Proceedings of the 2013 Fourth International Emerging Intelligent Data and Web Technologies (EIDWT ’13), pp. 241–248, IEEE, 2013. 
[5] R. L. Rivest, A. Shamir, and D. A. Wagner, “Timelock puzzles and timed release crypto,” tech. rep., Massachusetts Institute of Technology, 1996. 
[6] J. Li, W. Yao, Y. Zhang, and H. Qian, “Flexible and fine-grained attribute based data storage in cloud computing,” IEEE Transactions on Services Computing, Avaliable online, 2016. 
[7] Z. Qin, H. Xiong, S. Wu, and J. Batamuliza, “A survey of proxy re-encryption for secure data sharing in cloud computing,” IEEE Transactions on Services Computing, Avaliable online, 2016. 
[8] F. Armknecht, J.-M. Bohli, G. O. Karame, and F. Youssef, “Transparent data deduplication in the cloud,” in Proceedings of the 22nd 

[9] ACM SIGSAC Conference on Computer and Communications Security, pp. 886–900, ACM, 2015. R. Masood, M. A. Shibli, Y. Ghazi, A. Kanwal, and A. Ali, “Cloud authorization: exploring techniques and approach towards effective access control framework,” Frontiers of Computer Science, vol. 9, no. 2, pp. 297– 321, 2015. 
[10] K. Ren, C. Wang, and Q. Wang, “Security challenges for the public cloud,” IEEE Internet Computing, vol. 16, no. 1, pp. 69–73, 2012. 



