# CS305_Software_Security
Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?

The client was Artemis Financial and they were a financial firm wanting to revamp their software from a security perspective. They felt they were vulnerable to attacks and wanted us to lok at their application from the DevSecOps lense. They had lots of dependencies and wanted us to check for vulnerabilities within those libraries. Additionally, they wanted us to review their code manually to check for and/or improve any logic that left them open to attacks. 

What did you do particularly well in identifying their software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing? 

I thought one thing was being able to research the NVD site for the vulnerabilities and identifying ones that artemis needs to be worried about. This involved succesfully indentifying the value of the fix. Coming to the client with a knowledge of how the library is used within their application and in the same token, how the library vulnerability impacts the customer. One of the first things noticed about the dependency report is that it calls out every possible vulnerability and lists the evidence count as well as the severity. This evidence or CVE count can help us as security developers prioritize our work. Vulnerabilities with a high CVE count most likely have a fix in place as the CVE count addresses how common the vulnerability is. If it has a low evidence count then we know it is not a common vulnerability and may not be needed to be fixed...or at the very least may take longer to fix. 

What about the process of working through the vulnerability assessment did you find challenging or helpful?

Being able to see that lots of these issues had been solved and that there is such a large communnities of developers looking out for these issues is helpful. Lots of times the work has been done but you just need to apply it to your case. Additionally, simply putting in the dependency check code gives one a platform to begin thinking about software security. 

Employers sometimes ask for examples of work that you have successfully completed to demonstrate your skills, knowledge, and experience. What from this particular assignment might you want to showcase to a future employer?

I think being able to do the research and implement the fix, spend the time testing that fix, is valueable to employers. 
