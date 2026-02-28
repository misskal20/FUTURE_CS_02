Phishing Email Analysis
This project is part of my practical training where I analyzed a suspicious email to determine whether it was a phishing attempt.

Instead of just reading about phishing, I wanted to actually investigate one step by step — from checking the header to examining the content and authentication results.

What I Did

I took a suspicious email sample and performed:

Email header analysis

SPF, DKIM, and DMARC verification

Sender and return-path inspection

Content and social engineering analysis

Comparison with a legitimate email using 2-Step Verification

The goal was to understand how phishing emails bypass trust and how to technically detect them.

What I Found

After analyzing the header and authentication results:

SPF failed

DKIM was missing

DMARC failed

The sender domain did not properly match

The message used urgency and fear tactics

Based on both technical evidence and content analysis, the email was classified as a phishing attempt.

What I Learned

This project helped me understand that phishing detection is not only about tools. It also requires:

Attention to small details

Understanding attacker psychology

Knowing how email authentication works

Verifying links and domains carefully

It strengthened my practical email forensics and security analysis skills.

Disclaimer

This project was created for educational and cybersecurity training purposes only.
Any email samples, domains, or header data used were for demonstration and analysis practice.
