# CS-305
Artemis Financial is a highly respected financial organization that prides itself on security. They have a web-based application that they have used in the past. They have contracted Global Rain to bring the security level of their successful application up to modern standards. The functionality of the application is satisfactory, so no additional functionality has been requested. See the list below for a guideline of the client’s needs.
•	Protect Artemis customers’ confidential financial information
•	Comply with all international financial regulations
•	Focus is on external threats, but internal threats should be considered as well
•	Must protect against denial-of-service attacks

What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing? 

I did a good job at adding a SHA-256 cipher algorithm. This provided a high level of encryption for the data while in transit. I also added a self-signed certificate to enable secure communication over HTTPS. Software security is essential to protect the assets of the company, their customers, and the reputation of the company.

What part of the vulnerability assessment was challenging or helpful to you? 

I actually found the manual review to be particularly difficult. Determining what to look for and focus on was a challenge. Also figuring out how to specify the most recent spring boot version in the POM file and getting the updates was a little challenging, but after doing this, it seems straightforward. 

How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?  

I increased the layers of security by implementing cryptology and performing both static and manual testing. 

If I were to do manual reviews a lot in the future, I think a simple guideline or checklist should be developed.

How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

I ran multiple static tests and reviewed the vulnerability reports after each one. After bringing the spring boot version up to the latest version, I still had one dependency that showed up. I added this as an override under dependencies in the POM file to use the latest release of this dependency.
What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks? 

I think all the tools and practices introduced in the course are very useful. 


Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
I would show them the final vulnerability report that had zero detected vulnerabilities. I was very proud to get to this point. I am sure that vulnerabilities still existed that just had not been identified in the newer versions. However, the ability to update dependencies is crucial for success in code development. 

