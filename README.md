# Phishing Email Analysis

## Objective

In this email analysis project, my objective was to develop the skills and expertise necessary to proficiently analyze and counter phishing email threats. Through hands-on exercises, I learned to discern suspicious emails by examining sender information, content, and attachments for signs of malicious intent. By diving into email headers, metadata, file signatures, and URL analysis, I honed my ability to trace the origins of phishing attempts and assess their severity. Ultimately, this project empowered me with practical techniques and strategies to bolster email security posture and mitigate the risk of individuals falling victim to phishing attacks.

### Skills Learned

- Proficiency in analyzing phishing emails for potential threats and malicious content.
- Ability to identify common indicators of phishing attempts, such as suspicious sender addresses, incorrect grammar, and unexpected attachments or links.
- Experience in using email headers and metadata to trace the origin of phishing emails.
- Utilization of decoding methods to verify file type, read content, and extract hidden information. 
- Safely and effectively anaylze potentially dangerous attachments using virtual machines and online file reading tools. 

### Tools Used

- Notepad++ to investigate and analyze the .eml raw data, such as headers and signatures. 
- Cyberchef to decode base64 to hex/plaintext, allowing further analysis of the email contents.
- HxD to open files in hexadecimal, combined with Gary Kessler's file signatures to determine actual file extension/type.

## Steps
![image](https://github.com/TyDusseau/Email_Analysis/assets/168771739/61642f7a-612f-473a-b618-3bda20657389)
_Ref 1: Opened .eml file in Notepad++ to view raw data_



![image](https://github.com/TyDusseau/Email_Analysis/assets/168771739/5d1e4415-13de-47e7-9eb4-6cc2e9ce2e17)
_Ref 2: Decoded base64 into readable format_



![image](https://github.com/TyDusseau/Email_Analysis/assets/168771739/200a755f-c100-467f-bf1f-4e6d61a899a6)
_Ref 3: Verified file type by checking hex file signature (Hidden Zip file)_



![image](https://github.com/TyDusseau/Email_Analysis/assets/168771739/59bf94d3-7e49-4aaa-85a4-41e5c01f0285)

_Ref 4: Downloading the decoded base64 recovered a zip with 2 visible and 1 hidden file_



![image](https://github.com/TyDusseau/Email_Analysis/assets/168771739/46d76bc6-6333-4fa0-85bf-5c21326d8d09)
_Ref 5: Verifying file type of "Daughters Crown" via HxD_



![image](https://github.com/TyDusseau/Email_Analysis/assets/168771739/735a1e47-6720-43f7-a063-c83f8afec136)
_Ref 6: Successfuly verified both file types and changed/opened the new files_


![image](https://github.com/TyDusseau/Email_Analysis/assets/168771739/7418e7ef-e978-47c6-a5a7-5270c5bdf95d)
_Ref 7: Cleared formatting on the previously hidden xlxs sheet to find the "flag", the location of the war council_
