## Phising analysis using sample .eml file
This project simulates analysing phishing email using tools like virustotal, emlanalyser, MX Toolbox Email Header Analyzer, abuseipdb, etc...

## Tools Used
- [EML Analyser](https://eml-analyzer.herokuapp.com/)
- [MX Toolbox Email Header Analyzer](https://mxtoolbox.com/EmailHeaders.aspx)
- [VirusTotal](https://www.virustotal.com/)
- [AbuseIPDB](https://www.abuseipdb.com/)

## Steps Performed
- Imported '.eml' file to EML Analyser and clicked 'Analyse' button
- Analysed the report and answered a few questions
    - What is the full email address of the sender?
      - `banco.bradesco@atendimento.com.br`

    - What domain is used to send this email? (Check Return-Path or From)
      - atendimento.com.br

    - What is the sender’s IP address from the header?
      - 137.184.34.4

    - Is the sender IP blacklisted? (Check using AbuseIPDB or VirusTotal – Answer Yes/No)
      - Yes

    - What is the result of SPF authentication? (Pass / Fail / Neutral)
      - Fail

    - What is one suspicious URL or link found in the email body?
      - `https://blog1seguimentmydomaine2bra.me/`

## Screenshots
<img width="1920" height="1020" alt="Screenshot 2025-10-25 193314" src="https://github.com/user-attachments/assets/04baf969-c3b8-46f4-98c2-68acc3de8418" />
<img width="1920" height="1020" alt="Screenshot 2025-10-25 193736" src="https://github.com/user-attachments/assets/8232f6d7-f6c9-4913-baea-acd3be1c3714" />
<img width="1920" height="1020" alt="Screenshot 2025-10-25 193821" src="https://github.com/user-attachments/assets/e002d860-0a41-401f-9a57-d2af82fd97af" />

## Outcome
Successfully analysed phishing sample using tools such as virustotal, abuseipdb, eml analyser, etc...

## Note
This was a self-simulated lab exercise for learning and practicing.
