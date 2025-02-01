**Requirements Document** \- SD72 AI Integrated Learning Hub Feb. 02, 2025  
---

**Revision History**  
---

| Name | Date | Reason for Changes | Version |
| :---- | :---- | :---- | :---- |
| Initial Draft | Jan-31 |  | 1.0 |
|  |  |  |  |

1. ## Overview {#overview}

[1\. Overview	1](#overview)

[2\. Business Requirements (Lex and Jackson)	2](#business-requirements-\(lex-and-jackson\))

[2.1. Background	2](#background)

[2.2. Business Opportunity	2](#business-opportunity)

[2.3. Business Objectives	2](#business-objectives)

[2.4. Success Metrics	2](#success-metrics)

[2.5. Vision Statement	3](#vision-statement)

[3\. Scope and Limitations(Carter, Tyler)	3](#scope-and-limitations\(carter,-tyler\))

[3.1. Major Features	3](#major-features)

[3.2. Project Scope	3](#project-scope)

[3.3. Limitations and Exclusions	4](#limitations-and-exclusions)

[4\. Context Description (Taleo, Shawn, Tobias)	4](#context-description-\(taleo,-shawn,-tobias\))

[4.1. User Classes and Characteristics (Tobias)	4](#user-classes-and-characteristics-\(tobias\))

[4.2. Operating Environment (Taleo)	5](#operating-environment-\(taleo\))

[4.2.1. Hardware Compatibility	5](#hardware-compatibility)

[4.2.2. Operating Systems	5](#operating-systems)

[4.2.3. Integrations	6](#integrations)

[4.2.4. Internet and Performance	6](#internet-and-performance)

[4.3. Design and Implementation Constraints	6](#design-and-implementation-constraints)

[4.4. Assumptions and Dependencies	7](#assumptions-and-dependencies)

[4.4.1. Assumptions	7](#assumptions)

[4.4.2. Dependencies	7](#dependencies)

[4.5. Glossary of Terms	7](#glossary-of-terms)

[4.6. References	7](#references)

[10\.  AI Reflection	7](#10.-ai-reflection)

2. ## Business Requirements (Lex and Jackson) {#business-requirements-(lex-and-jackson)}

   1. ### **Background** {#background}

   Currently, SD72 faces a difficult challenge due to not enough educators relative to the number of students. Many students require additional support in their learning experience, but there are limited resources within the school district which makes personalized assistance impossible. Traditional teaching methods, such as relying on paper copies and keeping track of students' progress manually presents more obstacles for the educational staff as well. Additionally, not all students will have the same comprehension level, and the standardized pace of teaching may not be effective for every student. In today’s digital world, there is a growing need for accessibility options that can accommodate different learning styles and the challenge will be in creating a more efficient and inclusive learning environment. 

   2. ### **Business Opportunity** {#business-opportunity}

   SD72 has proposed an AI powered teaching platform as a solution designed to enhance the accessibility and quality of content which will adapt to individual learning styles and accommodate different disabilities. There is also a growing burden on educators which the platform seeks to alleviate

   3. ### **Business Objectives** {#business-objectives}

   **B01**: Increase retention of course materials by 15-25% of 75% of students within 3 weeks after implementation.

   

   **B02**: Reduce time spent by educators on course management, materials generation and deployment by 30% within 3 weeks of system implementation.

   

   **B03**: Increase platform accessibility by 15% for 50% of students at school and at home within a month and a half of system implementation.

   

   **B04**: Implement 5 accessibility options by the first release. 

      

   4. ### **Success Metrics** {#success-metrics}

   **SM-1**: After two months, application activity data shows that 75% of students use the application during class and 30% use it outside of class.

   

   **SM-2**: A decrease by 15-20% of requested EA hours within 2 months of system implementation.

   

   **SM-3**: The average rating from guardians and teachers on \[monthly\] satisfaction surveys for “educational quality”  increased by 2 points on a 1 to 10 scale within 4 months following initial release.

      

   5. ### **Vision Statement** {#vision-statement}

   For educators and support staff at School District 72 who need to efficiently utilize available resources while enhancing student learning support, the Online Educational Hub is an interactive learning platform that centralizes course content distribution, tracks student progress, and provides AI-powered clarification tools for immediate assistance. Unlike manual, paper-based course delivery and limited one-on-one educator support, our product improves accessibility, streamlines content management, and offers personalized AI-driven learning assistance to enhance student comprehension.

   

3. ## Scope and Limitations(Carter, Tyler) {#scope-and-limitations(carter,-tyler)}

   1. ### **Major Features** {#major-features}

   **FE-1:** Interact with an AI Chatbot that can interpret and explain existing course content, or generate supplementary content. (B01, B02, B03)

   

   **FE-2:** Upload, view, modify, and remove course content. (B02)

   

   **FE-3:** Upload, view, modify, and remove assessments. (B02)

   

   **~~FE-4:~~** ~~Upload, view, modify, and remove assessment submissions. (B02)~~

   

   **FE-5:** Provide, view, modify, and delete grading and feedback on assessment submissions. (B02)

   

   **FE-6:** View tabulated progress summaries for individuals or classes. (B01, B02)

   

   **FE-7:** Receive data-driven AI suggestions for areas of improvement for individuals or classes. (B01)

   

   **FE-8:** Edit system preferences manually, or with AI assistance. (B04)

   

**FE-9:** Create, manage, and use user accounts. (B01, B03)

#### 

**Figure 1** Partial feature tree for SD72 Educational Hub

2. ### **Project Scope** {#project-scope}

   SD72 has commissioned us to develop an AI-powered web-based learning platform, intended to support individualized student learning, improve overall content accessibility, and reduce educator’s time spent on the creation and distribution of content. The system will accomplish the above by supporting digital content distribution, AI-based content interpretation and generation, and data-driven AI individualized learning suggestions. This learning platform system aligns with SD72’s goal of improved student support and accessibility by allowing students to access course content and receive AI-driven support anywhere, and anytime.

   

   Project Scope Provide a short description of the software being specified and its purpose, including relevant benefits, objectives, and goals. Relate the software to corporate goals or business strategies.

   

   3. ### **Limitations and Exclusions** {#limitations-and-exclusions}

   **LE-1**: The web-app will only be available for use by School District 72\.

   

   **LE-2**: Multi-language support is not within the scope of this release.

   

   **LE-3**: An assessment due date view is not within the scope of this release.

   

   **LE-4**: The ability to create, view, modify, and remove announcements is not within the scope of this release.

   

   **LE-5**: The ability for in-app communication between users is not within the scope of this release.

4. ## Context Description (Taleo, Shawn, Tobias) {#context-description-(taleo,-shawn,-tobias)}

   1. ### **User Classes and Characteristics (Tobias)** {#user-classes-and-characteristics-(tobias)}

   This system has a reasonably wide scope of users that will be interacting with the system. These include students, guardians, educators, and system administrators present in District 72\.

      1. #### **Students**

   The first user class is a student. There is a wide range of types of students, with varying technological skills, accessibility needs and access to technology at home. Therefore, a simple, easy-to-access system on as many different devices as possible is key. Students’ satisfaction with the system is vital, as they will use the system as a hub, containing a plethora of tools in order to help support them with their classes. AI tools are at the forefront of this, generating supplementary practice materials and providing further personalised explanations on topics that each student struggles with. The system will also provide further useful features such as viewing grades, handing in assignments/homework and viewing important information in the form of announcements and a calendar. Students should not be able to perform administrative tasks; the system should be set up for them and their login will be provided to them by their school. 

      2. #### **Educators**

   Educators will also use the system, as they will use it to support them with teaching a cohort of students in an online classroom-like environment. Educators must be able to distribute classroom materials, assign quizzes and assignments to their students whilst also receiving insights regarding the performance of their students as they interact with the system. A good user experience of this system is vital for educators as there will be a wide scope of differing technical expertise \- a frustrating system would result in many educators opting out of using it entirely. Whilst educators won’t have full access to the system’s administrative tools, it is important that they are able to create an online classroom/group containing a list of students and manage students’ data relating to their classroom \- for example, modifying a student’s grade. System-wide managerial tasks should instead be handed off to a system administrator in order to ensure system security.

      3. #### **Super Users**

   System administrators are a form of a ‘super user’ \- allowing for a wide scope of administrative functionality regarding the system as a whole. System administrators would mainly be the IT department at the schools using the system, who have a reasonably high technical expertise.

      4. #### **Guardians**

   Guardians, another user of the system, will interact with it in order to help support their student(s)’ education. The guardian’s view should be fairly limited in order to account for student and educator privacy. The primary use of the system is to view the student(s) they are responsible for’s progress and grades within their classes, and a means of which to find contact information for their educators. This user group is the least of our priority, as they are likely to only rarely use the system, with many of them likely never even interacting with it at all \- preferring to speak directly to educators instead.

   2. ### **Operating Environment (Taleo)** {#operating-environment-(taleo)}

   The software will be a web application designed to operate on external servers, which will be accessible by all internet-enabled devices. The operating environment is designed to be flexible and accommodate the diverse technological infrastructure of schools and homes. The key considerations are as follows:

      1. #### **Hardware Compatibility** {#hardware-compatibility}

   **OE-1**: Usable on laptops, desktops, tablets and smartphones.

      2. #### **Operating Systems** {#operating-systems}

   **OE-2**: Supports Windows (7+), macOS (Catalina+), Linux, ChromeOS, iOS (12+), and Android (8.0+).

   **OE-3**: Fully functional across all web browsers (Chrome, Firefox, Safari, Edge, etc).

      3. #### **Integrations** {#integrations}

   **OE-4**: Integrates with MyEducationBC to send and obtain student transcripts.

   **OE-5**: Integrates with email services enabling teachers to send emails to guardians.

      4. #### **Internet and Performance** {#internet-and-performance}

   **OE-6**: Requires an active internet connection (no offline functionality).

   **OE-7**: Lightweight design ensures smooth operation on low-bandwidth networks and older devices.

   3. ### **Design and Implementation Constraints** {#design-and-implementation-constraints}

   **CO-1:** 

   The nature of this application to personalize help for each student would involve collecting and storing user information. Operating within School District 72, this would mean the application would have to obey privacy and user data laws of Canada’s Personal Information Protection and Electronic Documents Act (PIPEDA) and B.C.’s Freedom of Information and Protection of Privacy Act (FIPPA). Clause 27 in BC’s FIPPA would limit how we can collect medical and other personal information from the user and PIPEDA’s Fair Information Principle 5 – Limiting Use, Disclosure, and Retention would heavily limit how much student information the AI would be able to access. This could potentially limit the education hub’s ability to personalize school work or lessons.

   

   **CO-2:** 

   Since this web application is to be run on school devices and various personal devices, we would have to account for the fact that the devices don't have very powerful hardware. This would mean the AI can’t require high specifications on the local device. If this is the case, the AI should be hosted remotely. Additionally, this would limit any additional features we could implement that would take a lot of resources on the user’s device, such as an offline compatible feature. 

   

   **CO-3:** 

   The expectation is that the education system can be launched on every commonly used web browser. Making a web application that can run on multiple different browsers takes a lot of time to code. Given the project timeline, it may not provide a sufficient amount of time to implement this functionality.

   

**CO-4:**   
Since the education hub contains some user information, security is an important design consideration for the system. Being web based, utilizing an HTTPS protocol would be ideal. In order for our education system to use HTTPS, School District 72 would need to buy an SSL license which could conflict with the project budget. Also, secure web development uses specific coding practices which takes time to implement correctly, conflicting with the project timeline.

4. ### **Assumptions and Dependencies** {#assumptions-and-dependencies}

   1. #### **Assumptions** {#assumptions}

   **AS-1:** The following assumptions have been made about the project environment and user expectations:

   **AS-2:** School District Adoption: The majority of staff and teachers in District 72 will integrate the platform into their classrooms.

   **AS-3:** Device Availability: Schools will have access to devices for teachers and students to use.

   **AS-4:** Internet Connectivity: An internet connection is assumed for all users as the system will not have offline functionality.

      2. #### **Dependencies** {#dependencies}

   **DE-1**: Multiple Servers: AI hosting dependant on a third-party provider

   **DE-2**: Framework: dependant on React, an open source library for web and native user interfaces

   **DE-3**: Package manager: dependant on npm, a third-party package manager, for JavaScript development

   

   All these dependencies may introduce compatibility challenges in the future, such as dropped support for React.

      

   5. ### **Glossary of Terms** {#glossary-of-terms}

      

   6. ### **References** {#references}

King’s Printer. (n.d.). Freedom of Information and Protection of Privacy Act. [https://www.bclaws.gov.bc.ca/civix/document/id/complete/statreg/96165\_03\#section27](https://www.bclaws.gov.bc.ca/civix/document/id/complete/statreg/96165_03#section27)

Office of the Privacy Commissioner of Canada. (2020, August 13). *Pipeda Fair Information Principle 5 – limiting use, disclosure, and retention*. [https://www.priv.gc.ca/en/privacy-topics/privacy-laws-in-canada/the-personal-information-protection-and-electronic-documents-act-pipeda/p\_principle/principles/p\_use/](https://www.priv.gc.ca/en/privacy-topics/privacy-laws-in-canada/the-personal-information-protection-and-electronic-documents-act-pipeda/p_principle/principles/p_use/)

## 10\. 	AI Reflection {#10.-ai-reflection}

\===============================END==============================================================================================================  
AI version of the Report:

1. Overview  
2. Business Requirements  
   2.1 Background  
   2.2 Business Opportunities  
   2.3 Business Objectives  
   2.4 Success Metrics  
   2.5 Vision Statement  
3. Scope and Limitations  
   3.1 Major Features  
   3.2 Project Scope  
   3.3 Limitation and Exclusions  
4. Context Description  
   4.1 User Classes and Characteristics  
   4.2 Operating Environment  
   4.3 Design and Implementation Constraints

   ### **4.3.1. Core Web Application Constraints**

* **Security and Privacy Compliance:**  
  * Ensure adherence to regulations such as FERPA and COPPA.  
  * Protect sensitive data (student and teacher information) with robust encryption and secure authentication.  
* **Accessibility and Usability:**  
  * Design with accessibility in mind (e.g., WCAG guidelines) to support users with disabilities.  
  * Provide an intuitive, user-friendly interface suitable for students, teachers, and administrators.  
* **Scalability and Performance:**  
  * Architect the application to handle high concurrent user loads, especially during peak periods.  
  * Optimize data handling and processing to ensure efficient performance.  
* **Cross-Browser and Device Compatibility:**  
  * Ensure consistent functionality across various browsers and devices, including desktops, tablets, and smartphones.  
* **Integration with Existing Systems:**  
  * Enable smooth integration with current school management systems, databases, and third-party educational tools through standard APIs.  
* **Budget and Timeline Constraints:**  
  * Align design and implementation choices with available resources, budget, and projected timelines for development and maintenance.  
* **Data Backup and Recovery:**  
  * Implement reliable data backup strategies and disaster recovery plans to ensure data integrity and minimal downtime.

  ### **4.3.2. Chatbot Feature Specific Constraints**

* **Privacy and Data Security:**  
  * Maintain the same high standards of data privacy as the core application, ensuring secure handling of conversation data.  
* **Accuracy and Reliability:**  
  * Ensure the chatbot’s NLP engine interprets inputs correctly and delivers contextually appropriate responses.  
* **Real-Time Performance:**  
  * Design the chatbot to provide prompt, low-latency responses for a seamless user experience.  
* **User Experience (UX) Consistency:**  
  * Integrate the chatbot seamlessly into the existing web app design, ensuring consistency and ease of use.  
* **Scalability:**  
  * Ensure the chatbot can support an increasing number of simultaneous user interactions without performance degradation.  
* **Content Moderation:**  
  * Include measures to monitor and filter inappropriate content, ensuring a safe and productive communication environment.  
* **Contextual Awareness:**  
  * Enable the chatbot to maintain conversational context, particularly in the educational context where discussions can be complex.

  4.4 Assumptions and Dependencies

  ### **4.4.1. Core Web Application Dependencies**

* **Front-End Frameworks and Libraries:**  
  * JavaScript frameworks such as React, Angular, or Vue.js.  
  * CSS frameworks like Bootstrap or Tailwind CSS for responsive design.  
* **Back-End Frameworks and Languages:**  
  * Server-side frameworks such as Node.js with Express, Django (Python), or Ruby on Rails for managing business logic and APIs.  
* **Database Systems:**  
  * Relational databases (e.g., PostgreSQL, MySQL) or NoSQL options (e.g., MongoDB) to securely store user data and educational content.  
* **Authentication and Authorization Libraries:**  
  * Tools for managing secure login processes (e.g., Passport.js for Node.js or Django’s authentication system).  
  * Support for OAuth or SAML for integrating with existing school district authentication systems.  
* **API Integrations:**  
  * Third-party APIs for email notifications (e.g., SendGrid), calendar integrations, or other learning management systems.  
* **Cloud Services and Hosting Platforms:**  
  * Cloud providers such as AWS, Azure, or Google Cloud for hosting, storage, load balancing, and scalability.  
* **Security Tools and Libraries:**  
  * Libraries for input validation, encryption (e.g., bcrypt for password hashing), and secure data handling.  
* **Testing and Deployment Tools:**  
  * Unit and integration testing frameworks (e.g., Jest, Mocha, PyTest) and CI/CD pipelines (e.g., Jenkins, GitHub Actions).  
* **State Management Tools:**  
  * Depending on the chosen front-end framework, state management libraries (e.g., Redux for React) to manage application state effectively.

  ### **4.4.2. Chatbot Feature Specific Dependencies**

* **Chatbot Frameworks and NLP Libraries:**  
  * Chatbot development platforms such as Dialogflow, Microsoft Bot Framework, or Rasa.  
  * NLP libraries like spaCy or NLTK for language processing and understanding.  
* **Machine Learning Models:**  
  * Pre-trained or custom-trained models to enhance language understanding and response generation.  
* **Real-Time Communication Protocols:**  
  * Use of WebSockets or similar protocols to enable real-time chat functionality.  
* **Integration with Back-End Services:**  
  * APIs or middleware to connect the chatbot with the existing user database, educational content systems, or other school resources.  
* **Logging and Monitoring Tools:**  
  * Tools for tracking chatbot interactions, performance, and errors to support continuous improvement and ensure compliance.  
* **Content Moderation Services:**  
  * Third-party services or libraries that can detect and filter inappropriate language in real time.




**3.1 Project Scope**

* 

  1.   
     **LE-1:** The web-app will only be available for use by School District 72  
     **LE-2:** Multi-language support is not within the scope of this release.  
     **LE-3:** An assessment due date view is not within the scope of this release.  
     **LE-4:** The ability to create, view, modify, and remove announcements is not within the scope of this release.  
     **LE-5:** The ability for in-app communication between users is not within the scope of this release.

    
     * ~~Lots of students on IEPs are ESL, so the chatbot should include the ability to translate between languages~~  
     * ~~Program is only for use within School District 72~~  
     * **~~\*FE-5:~~** ~~View upcoming assessment due dates. (???)~~  
     * **~~\*FE-8:~~** ~~Create, view, modify, and remove announcements. (???)~~  
     * **~~\*FE-9:~~** ~~Communicate between users. (???)~~


  * **Major Features** Summarize the major features the product contains or the significant functions that it performs or lets the user perform. Details will be provided in Section 5, so only a high level summary is needed here. Organize the functions to make them understandable to any reader of the RD. Think about how users will use the features to ensure the list is complete. Also ensure that it does not include unnecessary features that sound interesting, but does not provide customer value.

  ![][image1]

  * ~~AI chatbot for asking questions on content~~  
  * ~~Create, upload, modify, and delete assignments/quizzes as Educators~~  
  * Create, upload, modify, and delete learning content as Educators  
  * ~~View tabulated grades and summaries of individualized areas of success and struggle as Educators~~  
    * Educator Features  
      * ~~Grade and provide feedback on student-submitted work~~  
      * ~~Receive data-driven summary of individual student progress, with personalized suggestions for said student~~  
      * ~~Create announcements (ability to choose which user groups to send them to)~~  
      * ~~View class metrics~~

    * Student Features  
      * ~~Ability to contact educators in-platform~~  
      * ~~View class materials~~  
      * ~~Access additional materials~~  
      * ~~Submit completed work~~  
      * ~~Obtain and interact with practice materials (both manually and Ai generated)~~  
      * ~~View assessment due dates (including testing)~~  
      * ~~Obtain assistance of AI tools~~   
    * Guardian Features  
      * ~~View child’s assessment progress/grades~~  
      * **See communication between child and educator**  
      * ~~Receive data-driven summary of individual student progress, with personalized suggestions for said student~~  
      * ~~Schedule meetings with educators~~  
      * ~~Receive and view announcements/attachments from educators~~  
  * **Project Scope** Provide a short description of the software being specified and its purpose, including relevant benefits, objectives, and goals. Relate the software to corporate goals or business strategies.  
      
  * **Limitations and Exclusions** List any product capabilities or characteristics that a stakeholder might expect but that are not planned for inclusion in the product or in a specific release. List items that were cut from scope, so the scope decision is not forgotten.  
      
    * Lots of students on IEPs are ESL, so the chatbot should include the ability to translate between languages  
    * Program is only for use within School District 72  
    * **\*FE-5:** View upcoming assessment due dates. (???)  
    * **\*FE-8:** Create, view, modify, and remove announcements. (???)  
    * **\*FE-9:** Communicate between users. (???)

		Scope can change; commitments here are not final. Scope can be looked at 

 **4\.	Context Description (Taleo, Shawn, Tobias)**

1. **User Classes and Characteristics (Tobias)**  
   **![][image2]**  
     
     
   This system has a reasonably wide scope of users that will be interacting with the system. These include **students**, **guardians, educators**, and **system administrators** present in District 72\.  
     
   The first user class is a student. There is a wide range of types of students, with varying technological skills, accessibility needs and access to technology at home. Therefore, a simple, easy-to-access system on as many different devices as possible is key. Students’ satisfaction with the system is vital, as they will use the system as a hub, containing a plethora of tools in order to help support them with their classes. AI tools are at the forefront of this, generating supplementary practice materials and providing further personalised explanations on topics that each student struggles with. The system will also provide further useful features such as viewing grades, handing in assignments/homework and viewing important information in the form of announcements and a calendar. Students should not be able to perform administrative tasks; the system should be set up for them and their login will be provided to them by their school.   
     
   Guardians, another user of the system, will interact with it in order to help support their student(s)’ education. The guardian’s view should be fairly limited in order to account for student and educator privacy. The primary use of the system is to view the student(s) they are responsible for’s progress and grades within their classes, and a means of which to find contact information for their educators. This user group is the least of our priority, as they are likely to only rarely use the system, with many of them likely never even interacting with it at all \- preferring to speak directly to educators instead.  
     
   Educators will also use the system, as they will use it to support them with teaching a cohort of students in an online classroom-like environment. Educators must be able to distribute classroom materials, assign quizzes and assignments to their students whilst also receiving insights regarding the performance of their students as they interact with the system. A good user experience of this system is vital for educators as there will be a wide scope of differing technical expertise \- a frustrating system would result in many educators opting out of using it entirely. Whilst educators won’t have full access to the system’s administrative tools, it is important that they are able to create an online classroom/group containing a list of students and manage students’ data relating to their classroom \- for example, modifying a student’s grade. System-wide managerial tasks should instead be handed off to a system administrator in order to ensure system security.  
     
   System administrators are a form of a ‘super user’ \- allowing for a wide scope of administrative functionality regarding the system as a whole. System administrators would mainly be the IT department at the schools using the system, who have a reasonably high technical expertise.  
 


   

   

   

    

   

   Identify the various user classes that you anticipate will use this product. User classes may be differentiated based on frequency of use, subset of product functions used, technical expertise, security or privilege levels, educational level, or experience. Describe the characteristics of each user class. Certain requirements may pertain only to certain user classes. Distinguish the favored user classes from those who are less important to satisfy.

   

   2. **Operating Environment (Taleo)**  
        
      Describe the environment in which the software will operate, including the hardware platform, operating system and versions, and any other software components or applications with which it must peacefully coexist.  
        
      The software will be a web application designed to operate on external servers, which will be accessible by all internet-enabled devices. The operating environment is designed to be flexible and accommodate the diverse technological infrastructure of schools and homes. The key considerations are as follows:

      1\. Hardware Compatibility:  
      **OE-1:** Usable on laptops, desktops, tablets and smartphones.  
        
      2\. Operating Systems:

      **OE-2:** Supports Windows (7+), macOS (Catalina+), Linux, ChromeOS, iOS (12+), and Android (8.0+).  
      **OE-3:** Fully functional across all web browsers (Chrome, Firefox, Safari, Edge, etc).  
      

      3\. Integrations:

      **OE-4:** Integrates with MyEducationBC to send and obtain student transcripts.  
      **OE-5:** Integrates with email services enabling teachers to send emails to guardians.

		  
4\. Internet and Performance:  
**OE-6:** Requires an active internet connection (no offline functionality).  
**OE-7:** Lightweight design ensures smooth operation on low-bandwidth networks and older devices.  
 

3. **Design and Implementation Constraints (Shawn)**  
   Describe any items or issues that will limit the options available to the developers. These might include: corporate or regulatory policies; hardware limitations (timing requirements, memory requirements); interfaces to other applications; specific technologies, tools, and databases to be used; parallel operations; language requirements; communications protocols; security considerations; design conventions or programming standards (for example, if the customer’s organization will be responsible for maintaining the delivered software).  
     
   CO-1 The nature of this application to personalize help for each student would involve collecting and storing user information. Operating within School District 72, this would mean the application would have to obey privacy and user data laws of Canada’s Personal Information Protection and Electronic Documents Act (PIPEDA) and B.C.’s Freedom of Information and Protection of Privacy Act (FIPPA). Clause 27 in BC’s FIPPA would limit how we can collect medical and other personal information from the user and PIPEDA’s Fair Information Principle 5 – Limiting Use, Disclosure, and Retention would heavily limit how much student information the AI would be able to access. This could potentially limit the application’s ability to personalize school work or lessons.  
     
   CO-2 Since this web application is to be run on school devices and various personal devices, we would have to account for the fact that the devices don't have very powerful hardware. This would mean the AI can’t require high specifications on the local device. If this is the case, the AI should be hosted remotely. Additionally, this would limit any additional features we could implement that would take a lot of resources on the user’s device, such as an offline compatible feature.   
     
   CO-3 Multi-platform → limited time  
   The expectation is that the education system can be launched on every commonly used web browser such as Chrome, Safari, Explorer, etc. Making a web application that can run on multiple different browsers takes a lot of time to code. Given the project timeline, it may not provide a sufficient amount of time to implement this functionality.  
     
   CO-4 Security → https needs SSL license, needs specific coding practices to be secure  
   Since the education system contains some user information, security is an important design consideration for the system. Being web based, utilizing an HTTPS protocol would be ideal. In order for our education system to use HTTPS, School District 72 would need to buy an SSL license which could conflict with the project budget. Also, secure web development uses specific coding practices which takes time to implement correctly, conflicting with the project timeline.  
     
   4. **Assumptions and Dependencies (Taleo,Shawn)**  
        
      List any assumed factors (as opposed to known facts) that could affect the requirements stated in the RD. These could include third-party or commercial components that you plan to use, issues around the development or operating environment, or constraints. The project could be affected if these assumptions are incorrect, are not shared, or change. Also identify any dependencies the project has on external factors, such as software components that you intend to reuse from another project.

      **1\. Assumptions**  
      The following assumptions have been made about the project environment and user expectations:  
* **School District Adoption**: The majority of staff and teachers in District 72 will integrate the platform into their classrooms.  
* **Device Availability:** Schools will have access to devices for teachers and students to use.  
* **Internet Connectivity:** An internet connection is assumed for all users as the system will not have offline functionality.  
* 

  

  **2\. Dependencies**

  DE-1 Multiple Servers: AI hosting dependant on a third-party provider

  DE-2 Framework: dependant on React, an open source library for web and native user interfaces

  DE-3 Package manager: dependant on npm, a third-party package manager, for JavaScript development

		All these may introduce compatibility challenges in the future

5. **Glossary of Terms**  
     
   Define all the terms necessary to properly interpret the RD, including acronyms and abbreviations.  
     
   6. **References**  
        
      List any other documents or Web addresses to which this RD refers. These may include user interface style guides, contracts, standards, system requirements specifications or use case documents. Provide enough information so that the reader could access a copy of each reference, including title, author, version number, date, and source or location.

     
10. **Reflection on the Use of AI** **Please provide two submissions for this deliverable. Firstly, provide the version of your RD that you did not use AI for. Secondly, provide the version of your RD that AI helped you generate. The version of your RD that relies on AI should contain a reflection on the use of AI based on the following questions:**  
      
1. List all the ways that your team used generative AI in this deliverable. Please be specific. (E.g. to identify potential user classes).

	NLP:

* Refining and Structuring Ideas  
* Ensuring Completeness for RD section requirements  
* Summarization and Rewording

	Research:

* Domain legal compliance  
* 

	Requirements Ideation

*   
    
2. Which AI model did you use? (E.g. ChatGPT 4o)  
     
3. What similarities and differences did you notice between your content and the content generated by AI?  
     
4. What aspects of the AI-generated artifact surprised you or that you hadn't considered? Why were you surprised? Provide examples.  
     
5. What are some areas where AI did not help you in writing these sections of the requirements document? Be specific about those areas.  
     
6. What did you do when AI’s content differed from your own content? How did you decide what content to keep? Give examples of the differences here.  
     
7. How confident were you in generative AI’s output?  
     
8. In your observations, what made prompts  effective and what made prompts ineffective? How did you decide that a prompt was effective, or not? Please give examples of your prompts for both good and bad prompts, and your perceived good and bad responses from the AI model.  
     
9. If you had to repeatedly prompt the AI model, why did you keep updating your prompt? What changes were you making to your prompts? How did you know when you were satisfied with the output? Give examples of conversations requiring repeated or changing prompts.  
     
10. Did you perceive that the AI model gained and maintained contextual understanding during the conversation? E.g. did you keep having to remind the model of something introduced early on? What context did it remember and what context did it forget?  
      
11. **Appendix**

**Reflection Use of AI**

**1\. List all the ways that your team used generative AI in this deliverable. Please be**  
**specific. (E.g. to identify key stakeholders)**  
We used generative AI to word our thoughts better, describe the company, generate  
stakeholders and schedules, and review our RFP structure and content.  
**2\. Which AI model(s) did you use?**  
ChatGPT 4o mini  
**3\. What similarities and differences did you notice between your content and the**  
**content generated by AI? Please give examples from your RFP.**  
The AI-generated content had a lot of similar ideas to our RFP. The scheduling system  
and profiling were both similar to the ideas we came up with as a group. The AI differed  
in our response by mentioning broader ideas. Instead of describing how and why the  
processes should be implemented, the AI mainly focused on the what factor. This was  
especially relevant in the intended users, where it mentioned that patients and  
healthcare providers are the intended users, and in the objectives section, where it  
mentioned increasing availability but now how, or the direction to go to solve that.  
**4\. What aspects of the AI-generated artifact surprised you or that you hadn't**  
**considered? Provide examples from your RFP.**  
The AI-generated response was beneficial as it had a quicker and broader knowledge of  
related aspects to a RFP. Certain regulations for constraints on the health, privacy and  
development side were overlooked when building the constraints. The AI also defined  
and simplified the current systems used in hospitals today which were implemented in  
the current systems section.  
**5\. What are some areas where AI did not help you in writing your RFP? Be specific**  
**about those areas.**  
The AI-generated prompts were very broad. We noticed that even with our problem  
definition, the results could have been applied to any industry. For the first few iterations  
the AI While there is overlap between industries, I was not as specific as we wanted it to  
be. The AI initially outlined a large majority of the document in bullet points. While this is  
good for learning and referring to, it was excessive even for an RFP.  
**6\. What did you do when AI’s content differed from your own content? How did you**  
**decide what content to keep? Give examples of the differences here.**  
While we did not incorporate any AI-generated content into our RFP, the AI-generated  
material aligned closely with our objectives and was repeating what we had already said.  
**7\. How confident were you in generative AI’s output?**  
We were confident in AI’s ideas, such as problem statement and project objectives, but  
we did not find its formatting and writing style to conform to our purposes with our  
background of requirements engineering.  
**8\. In your observations, what made prompts effective and what made prompts**  
**ineffective? How did you decide that a prompt was effective, or not? Please give**  
**examples of your prompts for both good and bad prompts, and your perceived**  
**good and bad responses from the AI model.**

**Prompt 1:**  
If you were tasked with creating a healthcare app as a business analyst with requirements  
engineering background, how would you create a request for proposal with the following  
Sections:

Product Overview, Project Objectives, Current Systems, Intended Users of the System, Known  
Interaction Within or Outside the Client Organization, Known Constraints to Development,  
Project Schedule

Problem Statement: Healthcare systems face long wait times for appointments, checkups,  
consultations, and more. There is a need to reduce these wait times to increase availability and  
access to essential services provided for all patients. Additionally, each patient has their own set  
of prescriptions, injuries, and other medical diagnoses and issues. These systems can be  
managed by a non-human, to increase healthcare provider availability, healthcare efficiency, …

**Prompt 1 Response Example:**

2\. Project Objectives  
● Reduce wait times for appointments, consultations, and checkups.  
● Increase accessibility to healthcare services for all patients.  
● Streamline healthcare workflows to improve healthcare provider efficiency.  
● Enable easy management of patient prescriptions, diagnoses, and medical history.  
● Automate routine tasks to reduce manual intervention, leveraging AI-driven solutions  
where applicable.  
● Enhance patient experience through an intuitive and user-friendly interface.  
● Ensure data privacy and security in compliance with healthcare regulations (e.g.,  
HIPAA, GDPR).

**Prompt 1 Reflection:**  
This turned out to be a bad prompt as it was littered with unhelpful bullet points and vague  
wording. In the example from the AI’s output above, having only bullet points makes it hard to  
read and does not conform to the typical ‘section’ of an RFP. The AI also did not include  
anything on how this project would accomplish the objectives.

**Prompt 2:**  
If you were tasked with creating a healthcare app as a business analyst with requirements  
engineering background, how would you create a request for proposal with the following  
Sections:

Product Overview, Project Objectives, Current Systems, Intended Users of the System, Known  
Interaction Within or Outside the Client Organization, Known Constraints to Development,  
Project Schedule

Problem Statement: Healthcare systems face long wait times for appointments, checkups,  
consultations, and more. There is a need to reduce these wait times to increase availability and  
access to essential services provided for all patients. Additionally, each patient has their own set  
of prescriptions, injuries, and other medical diagnoses and issues. These systems can be  
managed by a non-human, to increase healthcare provider availability, healthcare efficiency, …  
Use full sentences in paragraph format under each section.  
   
**Prompt 2 Response Example:**  
2\. Project Objectives  
The primary objective of this project is to develop a user-friendly healthcare application that  
reduces patient wait times while improving access to healthcare services. Specifically, the app  
should allow for online appointment bookings, virtual consultations, and the management of  
patient records such as prescriptions and medical diagnoses. The app should support both  
patients and healthcare providers, enhancing the overall efficiency of medical consultations and  
ensuring patients receive timely care. Another objective is to ensure data security and patient  
confidentiality by adhering to legal and regulatory requirements, such as HIPAA in the United  
States or GDPR in Europe. Additionally, the project aims to be scalable, allowing for future  
integration with new features and third-party systems.

**Prompt 2 Reflection**:  
This prompt had a better format as it did not use only bullet points in its response. However, it  
mentions some irrelevant details as it begins to talk about the United States and Europe. The  
project objectives it mentions are broadly correct, however are quite broad.This response was a  
clear improvement over the prompt 1 response.

**Prompt 3:**  
If you were tasked with creating a healthcare app as a business analyst with requirements  
engineering background, how would you create a request for proposal with the following  
Sections:

Product Overview, Project Objectives, Current Systems, Intended Users of the System, Known  
Interaction Within or Outside the Client Organization, Known Constraints to Development,  
Project Schedule

Problem Statement: Healthcare systems face long wait times for appointments, checkups,  
consultations, and more. There is a need to reduce these wait times to increase availability and  
access to essential services provided for all patients. Additionally, each patient has their own set  
of prescriptions, injuries, and other medical diagnoses and issues. These systems can be  
managed by a non-human, to increase healthcare provider availability, healthcare efficiency, …

Project Objectives:  
● Decrease wait time for appointments  
● Improve efficiency for report generation  
● Reduce overhead for hospital staff  
● Improve quality of care  
● Provide consistent way of patient prioritization  
Systems created (uses AI):  
Medical Profiling System, Scheduling Assistant (determining patient priority based on medical  
profile and urgency of the situation), Report Generation  
Use full sentences in paragraph format under each section.

**Prompt 3 Response Example:**  
Project Objectives:  
The primary goal of this project is to significantly decrease patient wait times for appointments,  
checkups, and consultations by optimizing scheduling and prioritization processes. The app will  
leverage AI-driven tools, including a Medical Profiling System and Scheduling Assistant, to  
enhance the workflow of healthcare providers. Additionally, it aims to improve the efficiency of  
generating medical reports, reducing the administrative burden on hospital staff. By reducing  
operational overhead, the project seeks to allow healthcare providers to focus more on patient  
care, ensuring that resources are allocated where they are most needed. The app will also  
provide a consistent and reliable system for patient prioritization based on urgency, ensuring the  
right care is delivered at the right time.

**Prompt 3 Reflection:**  
This prompt finally gave us an AI generated RFP that we were satisfied with. We were  
able to eliminate most of the unfavourable formatting and wording, replacing it with nice  
paragraphs that excluded irrelevant details included in the previous prompt.

**9\. If you had to repeatedly prompt the AI model, why did you keep updating your**  
**prompt? What changes were you making to your prompts? How did you know**  
**when you were satisfied with the output? Give examples of conversations**  
**requiring repeated or changing prompts.**  
We did have to repeatedly prompt the AI to get more specific answers that were more tailored to  
what we wanted. For example, for Prompt 2, we specified that we wanted full sentences and  
paragraphs for each section. This was to make it more similar to what a proper RFP should like  
and to get more fleshed out responses. For Prompt 3, we specified our project objectives so  
rather than getting a very general answer, it was more relevant to what we envisioned. We knew  
when we were satisfied with the AI’s response when it was becoming closer and closer to the  
RFP we created.

An example of a conversation that required changing the prompt is seen below.

**Prompt 2 Product Overview**  
The proposed healthcare app will be designed to address the inefficiencies present in current  
healthcare systems, particularly long wait times for appointments, checkups, and consultations.  
The app aims to streamline patient access to healthcare services by offering features such as  
appointment scheduling, telemedicine consultations, electronic health record management,  
prescription tracking, and appointment reminders. By integrating an AI-powered system for  
basic consultations and medical advice, the app seeks to increase provider availability, reduce  
patient wait times, and ensure that healthcare resources are utilized more efficiently.  
Additionally, the app will integrate with existing hospital or clinic systems to provide seamless  
access to patient records and history, ensuring continuity of care.

**Prompt 3 Product Overview:**  
This proposal outlines the development of a healthcare application aimed at improving the  
efficiency and accessibility of healthcare services. The app will integrate artificial intelligence  
(AI) to manage medical profiling, scheduling, and report generation. It will focus on reducing  
wait times for patients, improving overall healthcare delivery, and streamlining hospital  
operations. By automating and prioritizing tasks that traditionally consume significant staff  
resources, the application will ensure timely care and enhance the quality of service provided to  
Patients.

Without giving the AI our specific objectives, it generated an overview that had an objective we  
did not want, such as the telemedicine consultations as seen in Prompt 2\. But after providing  
the objectives, the product overview for Prompt 3 was concise, yet contained almost the same  
details as our own product overview.

**10\. Did you perceive that the AI model gained and maintained contextual**  
**understanding during the conversation? E.g. did you keep having to remind the**  
**model of something introduced early on? What context did it remember and what**  
**context did it forget?**

The AI model did maintain contextual understanding during the conversation. Starting from  
prompt 1 and continuing the conversation with the model to remove bullet points than include  
more about are project objectives and systems worked well. The model was able to maintain the  
details from the previous prompt while adding what was asked of it well.

[image1]: <data:image/png;base64,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>

[image2]: <data:image/png;base64,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>