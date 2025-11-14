# Task 2 – Phishing Email Analysis

This repository contains the work completed for Task 2 of the Cyber Security Internship.  
The objective of the task was to analyze a suspicious email by examining its header using free online tools and identifying phishing indicators based on the results.

## Files Included
- phishing-email.txt  
  Contains the phishing email sample used for analysis.

- email-header.txt  
  Contains the raw email header that was used in the header analysis tools.
  
- screenshot  
  A folder containing screenshots from MXToolbox and other tools used during the analysis.

## Tools Used
The following free online tools were used for the analysis:

1. MXToolbox Email Header Analyzer  
   https://mxtoolbox.com/EmailHeaders.aspx  
   Used to analyze SPF, DKIM, DMARC, relay information, and IP reputation.

2. Google Message Header Analyzer  
   https://toolbox.googleapps.com/apps/messageheader/  
   Used to verify routing patterns and authentication results.


## What Was Done
1. A phishing email sample was created and saved.  
2. The header of the email was analyzed using MXToolbox.  
3. Authentication results (SPF, DKIM, DMARC) were examined.  
4. The relay server and originating IP were inspected.  
5. Domain names, return-path values, and reply-to fields were reviewed.  
6. Indicators of spoofing and social engineering were documented.  
7. A full phishing analysis report was prepared based on the results.

## Conclusion
The analyzed email exhibited all major signs of phishing, including failed authentication checks, suspicious sender domains, the use of foreign hosting servers, and the presence of a deceptive reply-to address. These findings confirm that the email was not legitimate and was created to deceive the recipient.
