# Task_02_Elevate_Lab
##  Analyze a Phishing Email Sample
   The image upload is the sample example of phising email from hooksecurity.com site
   After analyzing this email,
   1. Sender's email address
      support@msupdate.net  : not an official Microsoft address.  
      msupdate.net is not a legitimate Microsoft domain.   
      Official Microsoft email domains are: @microsoft.com, @accountprotection.microsoft.com, @security.microsoft.com   
      Red flag: Attackers tend to use domains that appear similar to authentic ones in an effort to impersonate trusted senders.    
      In this instance, msupdate.net is probably an attack domain pretending to be Microsoft.    

 2. Email Header Check 
    We can't see the full raw headers in the screenshot. We can check the header by using tools like Google Header analyzer and MXToolbar Email header analyzer

3. Suspicious Links or Attachments
   Links Present:       
  "Reset your password"      
  "Review your security info"       
  "Learn how to make your account more secure"   
  Potential Risks:    
    Anchor text alone is not sufficient. You need to hover to view the URL.   
    Any link that points to a non-Microsoft domain (login-verification.msupdate.net or micros0ft-reset.info, for example) is probably a phishing trap.   
    No attachments found in this case, which is typical of phishing emails designed to steal credentials rather than provide malware.   

4. Urgent or Threatening Language
   "If this wasn't you, your account has been compromised."    
    The message is crafted to make the user panic and respond hastily without scrutinizing it.    
    Phishing Technique Identified: Attackers resort to psychological manipulation (account compromise fear) to coerce the victim into clicking on the malicious link.   

5. Mismatched URLs   
  Without hovering over the links (not visible in the screenshot), we can't determine actual mismatches.   
  But there is still the risk: visually legitimate links may point to phishing sites with spoofed login pages.   
  Look for: misspelled domains (i.e., micr0soft.com, microsoft-reset.com, ms-support.net).   

6. Spelling or Grammar Errors    
    This sample is well-written with no apparent spelling or grammar errors.  

Conclusion:   
  Most contemporary phishing emails are grammatically correct and professional in appearance. Error-free does not equal authenticity.   
  Although this email appears professional, its unverified origin, urgency tone, and suspicious domain indicate a phishing attack meant  to acquire login credentials or personal data.   
  To make others aware, explain:    
  Never click on links without checking the domain.   
  Always inspect sender addresses and headers.    
  Turn on two-factor authentication.   
    Inform your IT department or email provider about phishing emails.     
