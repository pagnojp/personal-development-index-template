- Why might being required to change our passwords regularly actually pose a threat to our security?
  
Hackers can get access to all passwords and get hints about the new password, becoming more vulnerable 
to brute force attacks. Users tend to do minimal changes to easy remember the password, making it more predictable.

- If I have a six-character password consisting of uppercase (English) letters and (decimal) digits only, how many seconds might it take an adversary to crack, assuming they make one attempt per second?
  
26 uppercase letters + 10 decimal digits = 36 possibilities
36^6 = 2,176,782,336 seconds

- Password Game result: (rule 12)
pepsiXXXVapril%yd7558tallySi

![comic](https://github.com/pagnojp/personal-development-index-template/blob/75188192fd333cf5444f5e3a4ac2056db6fbf3e8/courses/cs50-introduction-to-cybersecurity/Untitled.png)

- Consider the top row of the comic above. Why are passwords like those easy (for a computer) to guess but hard (for a human) to remember?

Easier to a computer guess because the patterns and substitutions have a limited number of possible combinations, could be tested in brute force and dicionary attacks.

- Now consider the bottom row of the comic above. Why are passwords like those hard (for a computer) to guess but easy (for a human) to remember?

Hard for a computer guess because the number of possible combinations is very larger and words sequence is hard to combine in a dictionary or brute force attack 
because it would take a long time to test.

- What is a "credential stuffing" attack?
Is a attack where hackers uses a list of of already known usernames and passwords from other applications, because is common users use the same credentials in accross diferent applications.

- Provide a specific example of something that would be considered a type of knowledge factor for authentication purposes.
Do NOT provide any of your own knowledge factors (or anything resembling them) themselves as an answer to this question. We are looking for you to answer the question in the general sense (a "type of").
If you provide an answer that is, or appears to be, an actual specific knowledge factor, the answer WILL be marked incorrect, without exception, and you should consider that knowledge factor to have been compromised.

Something like a password.

- Provide a specific example of something that would be considered a type of inherence factor for authentication purposes.

biometrics, fingerprints, face

- Why are phishing attacks so difficult to prevent?

Because hackers prey on your trust for those certain companies or persons. Trying to prey on your comfort with familiar user interfaces, things that you've seen before. It's too easy for an hacker to make a very official-looking application

- Suppose that your boss asks you whether the company should require use of password managers for all employees.
Explain in a short paragraph why you might want everyone in the company to use a password manager. 

To enhance the company's security by ensuring that all users have unique and complex passwords, reducing the risk of credential stuffing due to password reuse. Makes easier centralizing the password management.
