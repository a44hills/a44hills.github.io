# Welcome to my ePortfolio!
<br><br>


### Introduction: <br>
Within my ePortfolio, displayed are artifacts that I have selected that demonstrate some of my capabilities in software development. Areas highlighted include Software Design and Engineering, Algorithms and Data Structures, and Databases. The artifacts selected are from previous software courses I completed at Southern New Hampshire University. 

After selecting the artifacts, I performed a code review of each artifact describing the current code status and structure, identifying security vulnerabilities and where enhancements will be made to address these issues. Enhancements to the artifacts were made, showcasing my abilities and talents in software development, algorithms/data structures, and databases.<br>
<br>
<br>

### About Me:<br>
I am a U.S. Navy veteran. Growing up in Denver, I am a die-hard fan of the Colorado Avalanche, Colorado Rockies, Denver Broncos, and Denver Nuggets. Not into the snow, so when I was Blessed and offered a job in Santa Clara Ca, I took it, and my wife, and I have lived here ever since! Living in the Sacramento area now, we have the best of both worlds – snow if we want to see it, and then run down to the ocean to warm up.

I am attending Southern New Hampshire University and completing my undergraduate degree. My next step is already in the works, which is staying at SNHU and obtaining my Master's in IT with a concentration in Software Application Development.

With my education, my plans are to transfer into a software development team, develop secure reliable applications, and resolve customer requirements. Long-term goals include leading development teams and possibly looking into management. This too is open and has the potential to change.<br>
<br>
<br>


<!-- ### [Self Assessment:](https://github.com/a44hills/CS499/blob/main/Self%20Assessment.docx) <br> -->
### [Download Self Assessment:](https://github.com/a44hills/CS499/blob/main/Self Assessment.docx) <br>

<br>
<br>


## Enhancments:<br>
### Description: The Enhancements -<br>
This document describes the enhancements that were made to the three artifacts that I selected to showcase my abilities in the areas
of Software Engineering and Design, Algorithms and Data Structures, and Databases. The enhancements made in the artifacts reflect improvements
to the quality, addresses limitations or inconsistencies that were identified, and/or mitigate vulnerabilities.
<br>
<br>


## Code Review:<br>
### Description: The Code Review -<br>
In the presentation, I will be conducting the code review on three different projects from previous courses that I have taken here at 
Southern New Hampshire University. The purpose of the code review is a standard practice in the Software Development Life Cycle, for 
improving deliverables and user experiences while ensuring that code is concise, well-commented, and ready for updates. 
In this code review, I will discuss the code that relates to three key computer science categories: Software Engineering and Design, 
Algorithms and Data Structure, and Databases. I will analyze existing code for weaknesses, limitations, and vulnerabilities and explain 
my plan for enhancements. During the code review, I will utilized the CS-499 Code Review Checklist.<br>

### [Code Review - Redirects to Code Review YouTube Video](https://youtu.be/vR5F8SCNP6M)  <br>
<br>
<br>



## Software Engineering and Design: <br>
### Description: The Software Engineering and Design - <br>
The artifact that I used to meet the ePortfolio requirements, and to represent my growth in the areas of software design/engineering, is to use the Software Reverse Engineering Project 2 – Common Security Issues that may be identified through reverse engineering. The artifact is the final C++ file submitted, in which I had to reassemble the C++ file from the binary source code supplied in the course. Before reassembling the file, I was required to identify the blocks of assembly code and describe what the different blocks of code performed.

After reassembling the binary code into a C++ file, I had to identify where multiple security vulnerabilities are present within the various methods in the C++ file. Within each method, comments were placed at the locations where the security vulnerabilities are located and described recommendations for how the vulnerabilities can be fixed. This artifact is provided from the CS-410 course taken in 22EW3.

The inclusion of this artifact into my ePortfolio will demonstrate my ability to read and comprehend both assembly code, and my ability to reverse engineer both assembly and C++ code. The selection of the project 2 C++ file demonstrates the various software vulnerabilities that I identified during the analysis of the reassembled code. Components within the source code involve minimizing the vulnerabilities by adding additional input code verification procedures, the addition of a login screen, allowing the user to create a unique user account, and encrypting the username/password file. These improvements will demonstrate the importance of security and reducing the ability of unauthorized users or malicious code to gain access to the system.

This project is currently meeting the course objectives outlined to meet the enhancements in Module One. Updates to the project include the following:

        •	Login screen allowing the user to –
            o	Log into the application
            o	Create new user accounts
            o	Find password

Additional enhancements completed user input verification routines, username, and password verification, and checking for invalid characters. The remaining item is the encryption of the username/password, using a valid secure encryption algorithm as outlined in Figure 1. 

In the Software Design Engineering enhancement, the skills that are illustrated and course outcome(s) of these skills align to [CS-499-05] “Develop a security mindset that anticipates adversarial exploits in software architecture and designs to expose potential vulnerabilities, mitigate design flaws, and ensure privacy and enhanced security of data and resources”. By enhancing the security and reducing the vulnerabilities in adding encryption to the username/password file and adding additional user input verification code to the enhanced Project 2 C++ file from CS-410, alignment in software development skills will be displayed. Name of the enhanced C++ file is CS499_SWE_Project2.cpp.

During the process of performing the enhancements and making the required changes to improve the security of the application, I found that this is what I have been fortunate to do during my career working as both a software validation engineer, BIOS engineer, and software applications engineer. The process of adding new features, making revisions, or updating the application to resolve issues is part of the job of being a software developer. Depending upon the organization, a large part of the job as a junior or middle engineer will find themselves resolving issues and adding new features to existing applications. Again, depending upon the company, application design is usually performed by middle engineers, and senior engineers are usually looking at management or becoming team leads, and leading a team of engineers and technicians. 

For this project, I am using a simple encryption/decryption algorithm, in which I am adding 3 to the ASCII character to encrypt or subtracting 3 from the ASCII character to decrypt. This provides a sample demonstration of how encryption/decryption would be implemented to protect the username/password. In a fully functional application, the algorithms would be in a separate protected file. The type of algorithm would also be more sophisticated and follow the current Advanced Encryption Standard (AES) with 128-bit key or longer encryption guidelines.

The challenges that I encountered while debugging the new enhancements, was in using the built-in cin method, where when it is called for the first time in the method, it would only accept the first character, and drop the rest of the username or password stream. To resolve this issue, I wrapped the cin method in the getline() method – getline(cin, username). Using this method, I was able to check the username and userpasswd using the VerifyUserNameInput() and VerifyPassWordInput() methods. 


Software design/engineering Zip file:

The included zip file includes the following artifact

        •	CS499_SWE_Project2.cpp file
    
            o	Contains the enhanced Project 2 C++ code
        
        •	CS499_SWE_Project.exe
    
        •	Database.txt file
    
            o	Contains sample usernames and passwords after encryption. Subtracting 3 from the ASCII value reveals the user/password:
	               yhud kloo		vera hill
	               wld kloo		        tia hill
	               mlp kloo		        jim hill
	               mrh vplwk		sam smith<br>

<!-- ## Software Engineering and Design: <br> -->

### [SWE Project 2](https://github.com/a44hills/CS499/blob/main/CS499_SWE_Project2.cpp) <br>
### [SWE Project 2 Zip File](https://github.com/a44hills/CS499/blob/main/CS499_SWE_Project2.zip) <br>
<br>


## Algorithms and Data Structures:<br>
### Description: The Algorithms and Data Structures:<br>
Data Structure Analysis:

Advantages of using data structures in software programs –
•	Data structures are efficient in the storage of data
•	Provides an efficient method of processing small and large amounts of data
•	Utilizing the correct data structure in a software program, time is saved in the processing of or retrieval of various sizes of data
•	Data structures that are properly designed, can aid in data operations like addition, deletion, manipulation, retrieval, and storage. Data structures of the type of Array, stacks, queues, linked list, and trees.
•	Data structures are reusable

Disadvantages of using data structures in software programs –<br>
•	A small change in the data can cause a large change in the structure of the decision tree.
•	Using data structures requires qualified professional resources to maintain the data structure.


Algorithm Analysis – Worst, Average, and Best:<br>
In analyzing an Algorithm for Worst, Average, and Best cases, the factors involved that will determine the outcome include the size of the input values, the data, and how it’s already arranged (order of the data to be sorted). For example, if the data to be sorted is already in order, or if the data item is not present, then when the algorithm is used the results would be determined to be worse than if the data was unsorted.

To determine the worst case, the upper limit of the execution time will be calculated. This is required to know what cases will cause the execution of the maximum number of operations. In the case of a linear search, where the data value is not present, the search method compares all elements of the array one by one. In this case, the temporal complexity of the worst-case search would be O(n).

For average-case analysis, all possible inputs are calculated to obtain the computation time. The results are then added and divided by the sum by the total number of inputs. This calculation is necessary to determine the distribution of cases. Again, using a linear search, and assuming that all the input cases are distributed in a uniform manner, the cases are added and divided by the sum by (n + 1).

In the calculation for the best-case analysis, the lower bound of the execution time is calculated. This calculation is necessary for knowing which case will cause the execution of the minimum number of operations. When using a linear search, the best case will occur when the data is present at the first location. In this case, the number of operations used will be constant. Here, the best-case time complexity would be O(1). See Figure 1 and Figure 2.

Conclusion:<br>
For algorithms like Sort by merge, the sorting will perform O(nLogn) operations for all cases. For other sorting algorithms, they will present the worst and best cases. In the case of a Quicksort, the worst-case scenario occurs when the input is already sorted, and the best case will occur when the pivot elements always divide the table into two halves. When performing an Insert sorting algorithm, the worst case will occur when the data input is already sorted, but in reverse order, while the best case will occur when the data input is sorted in the order of the output.<br>

### [Figure 1: Big O Complexity Chart](https://miro.medium.com/max/1200/1*j8fUQjaUlmrQEN_udU0_TQ.jpeg) <br> 
### [Figure 2: Common Data Structure Operations and Array Sorting Algorithms](https://rubydoobiedoo.files.wordpress.com/2016/09/region-capture-2.png) <br>


### [BinarySearchTree.cpp](https://github.com/a44hills/CS499/blob/main/BinarySearchTree.cpp) <br>
### [HashTable.cpp](https://github.com/a44hills/CS499/blob/main/HashTable.cpp) <br>
### [LinkedList.cpp](https://github.com/a44hills/CS499/blob/main/LinkedList.cpp) <br>
### [VectorSorting.cpp](https://github.com/a44hills/CS499/blob/main/VectorSorting.cpp) <br>
<br>



## Databases: <br>
### Description: Databases <br>
Databases:<br>
The artifact that I used to meet the ePortfolio requirements, and to represent my growth in the areas of databases, is the Client/Server Development – Project 2: Web Application Dashboard (Python Code). The project consists of a database and establishes successful CRUD routines in Python for MongoDB. In addition, a fully functional MongoDB dashboard was created, allowing the client, Grazioso Salvare, to interact with and visualize the database. This artifact is provided from the CS-340 course taken in 21EW1.

To enhance the project, I developed additional queries that will allow users to filter the database. In addition to the queries, interactive options through which users will activate the filters, and added a widget for dynamic presentations of retrieved data. The additional queries are used for displaying the additional different types of Birds and Cats the origination also works with. The queries will select – All Birds, Male Birds, Female Birds, All Cats, Male Cats, and Female Cats. See Figure 5: Additional Animals Pseudocode. This addition is incorporated into a revised ProjectTwoDashboard.ipynb Python file. In addition to the new queries, I also added a widget: a Date Picker Single (DatePickerSingle) located at: https://dash.plotly.com/dash-core-components/datepickersingle, which is applied to the main screen, along with the Grazioso Salvare logo. This additional widget provides a better user experience, along with a professional browser look.

Further enhancements include the addition of driver code to the Pie Chart call-back procedures. The driver contains two additional dropdown boxes, where the user can select the type of animal in the first dropdown, and the sex of the animal in the second dropdown. By default, the pie chart will display Dogs/All. This code is still under development, with the driver code commented out in order to prevent code from interfering with the proper use of the main application.

The skills that are illustrated and course outcome(s) these skills align to [CS-499-04] “Demonstrate an ability to use well-founded and innovative techniques, skills, and tools in computing practices to implement computer solutions that deliver value and accomplish industry-specific goals” in the Final Project Guidelines and Rubric. By enhancing the project, I am demonstrating how to apply database systems concepts and principles in developing client/server applications that interface client-side code with databases. 

During the development of the new queries and the addition of the widgets, no major issues arose, until I tried to access MongoDB in the Apporto (Virtual Lab). After logging into the virtual lab, I found that the App Store no longer contained the applications necessary to access the MongoDB or the Linux virtual server. To access the Linux server the Client-Server application is required. It appears that the applications have been disabled and made unavailable since I have completed the course. At this point, the code that I am enhancing will contain the new software changes and will be debugged by using the code review process and verifying that the code does not contain visible code vulnerabilities.<br>


### [Python CRUD File](https://github.com/a44hills/CS499/blob/main/CS340_Project_1.py) <br>
### [MongoDB Dashboard](https://github.com/a44hills/CS499/blob/main/ProjectTwoDashboard.ipynb) <br>
<br>






You can use the [editor on GitHub](https://github.com/a44hills/a44hills.github.io/edit/main/index.md) to maintain and preview the content for your website in Markdown files. <br>

<!---

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```


For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/a44hills/a44hills.github.io/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out. --->
