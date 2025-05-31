# cybersecurity--task-2  Phising E-mail Analysis 

# Objective
   To identify phishing characteristics in a suspicious email.

# Step-by-Step Analysis

1. Obtain a Sample Phishing Email
Sender email: security-update@paypa1.com
✅ Sample obtained

2. Examine the Sender’s Email Address
Real PayPal uses @paypal.com

This uses paypa1.com — "1" instead of "l"
🔴 Spoofed domain

3. Check the Email Header
Tools like MXToolbox reveal:

SPF fails

Not sent from PayPal servers
🔴 Header mismatch

4. Identify Suspicious Links/Attachments
Fake link: https://paypal.verify-account.info

ZIP attachment: may contain malware
🔴 Dangerous content

5. Look for Urgent Language
“Verify within 24 hours...”
🔴 Creates panic to rush you

6. Mismatched URLs
Hovering shows a different link than it claims
🔴 Fake and misleading

7. Spelling/Grammar Errors
No errors, but robotic tone
🟡 Impersonal and suspicious

8. Summary Table
Indicator	Result
Fake sender address	✅ Spoofed (paypa1.com)
Header mismatch	✅ SPF failed
Suspicious link	✅ Fake domain used
Attachment	✅ Malicious ZIP file
Urgent language	✅ Creates fear/pressure
Mismatched URLs	✅ Misleading real vs shown
Grammar/tone issues	🟡 Generic and robotic

# Final Conclusion
This email is a phishing attempt. It uses deception, urgency, fake links, and a spoofed email to trick the user.

  * Never trust such emails. Always verify links and sender addresses.

