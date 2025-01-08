# Phishing Email Analysis

## Objective

To conduct detailed analysis of phishing emails by evaluating email headers, attachments, links, and content for indicators of compromise, with the goal of identifying malicious intent, preventing potential breaches, and improving the overall security posture through timely detection and response.

### Skills Learned

- Understood and analyzing email headers (such as "From," "Reply-To," "Received" fields).
- Evaluated email attachments for malware or malicious content. eg. PDF, Excel
- Utilized threat intelligence platforms to cross-reference domains, IPs, and other indicators of compromise (IOCs)
- Familiarized with tools such as Cyber Chef, Gary Kerler, and exittool for verifying links, attachments, and domains.

### Tools Used

- Cyber chef used for copying plaintxt and decode it.
- Gary Kesler tool, To check filetye attached in suspicious email.
- exit tool, To find malicious act.
- Kali Lunix.

## Steps
- Download the Email File.
- Open and edit in Notepad.
- Analyse the Email and Check for SPF status Pass/Fail.
- If SPF status is Fail, then email might be suspicions, dig more into it.
- Check for ReplyTo mail and From Address must be same.
- Copy the Plaintext and try to decode it by using trsuted tool Cyber Chef.
- Then after message is been decoded copy first four byted and use Gary kelser tool to check the filetype.
- Check for the email service a malicious actor used. Here it was 'emkei' i;e face mails tool that creates and sends fakemails.
