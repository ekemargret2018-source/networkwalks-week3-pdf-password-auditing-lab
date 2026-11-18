# networkwalks-week3-pdf-password-auditing-lab
Week 3 cybersecurity practical on PDF password recovery and password security.
# Week 3 Project: PDF Password Recovery and Password Security

## Overview

This project explores password security and how password-auditing tools can be used to assess the strength of passwords protecting PDF documents.

The practical exercise focused on extracting password-verification data from a password-protected PDF and testing possible password combinations using a password list.

A PDF's original password is not simply stored as readable text. Its security mechanism uses password-derived data and encryption to protect the document. For supported PDF formats, tools can extract the relevant security data for offline password testing.

## Objectives

- Understand the difference between encryption and hashing.
- Learn how password recovery and password-auditing tools work.
- Understand how dictionary-based attacks test common password guesses.
- Identify why weak and predictable passwords are vulnerable.

## Tools and Technologies

### Tools covered in the session

- **John the Ripper (JtR Jumbo):** A command-line password-auditing tool that supports different password hash and encrypted-file formats.
- **Johnny GUI:** A graphical interface for John the Ripper.
- **Networkwalks Hash Calculator and Password Cracker:** Browser-based tools used for the practical exercise.

## What I Did

1. Worked with a password-protected PDF provided for the training exercise.
2. Extracted the PDF's password-verification data using the available extraction tool.
3. Loaded the extracted data into a password-recovery tool.
4. Tested possible passwords using a list of candidate passwords.
5. Successfully recovered the password for the training PDF and verified it by opening the document.

## What I Learned

- **Encryption:** Protects information by transforming it into an unreadable form that can be accessed with the correct key.
- **Hashing:** A one-way process used to generate a fixed representation of data. It is not designed to be reversed to reveal the original input.
- **Dictionary attacks:** Test passwords from a prepared list of common words and password combinations.
- **Password strength:** Short, predictable and commonly used passwords are easier to guess than long, unique and unpredictable passwords.
- **Password auditing:** Helps identify weak passwords and improve an organisation's password security practices.

## Key Takeaway

This exercise helped me understand how password-protection mechanisms work and why strong passwords are essential.

Using long, unique passwords, avoiding common password combinations, and enabling multi-factor authentication where available are important steps towards improving account and information security.

## Ethical Considerations

This exercise was carried out for educational purposes using a training document. Password-recovery tools should only be used on files and systems that you own or have explicit permission to assess.

---

**Learning Track:** Networkwalks Cybersecurity Internship
**Week:** 3
**Topic:** Password Hashes and Password Recovery
