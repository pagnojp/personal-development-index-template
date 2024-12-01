- Via what technique(s) might a malicious actor "crack" software (that is, bypass registration/payment to use it)?

Arbitrary code execution

- Distinguish the nature of two types of "cross-site" attacks we discussed: cross-site scripting (XSS) and cross-site request forgeries (CSRF).

XSS, is a form of attack where a website is tricked into running malicious code via a user’s input. CSRF is a ability to trick a user into executing commands on another website.

- Why do we need to escape certain characters in inputs?

To protect against attacks, escaping potentially troublesome characters.

- In the context of SQL, what is a prepared statement?

Are pre-designed snippets of code that correctly handle many database functions, including user input, to ensure that user-inputted data is properly escaped.

- Why is client-side validation considered "less secure", perhaps, than server-side validation?

Because in the client side the user can modify the code, for example, using the browser developer tools and manipulating the validation. Server-side validation provides security features to ensure that user input is appropriate and safe.

- Pragmatically, the above comic may be correct as it pertains to the behavior of most users towards open-source software. Even if that is your attitude towards it, why might it still be a good thing to consider using more open-source software (or, developing it), from a security-minded perspective? 

Open-source code is published readily online for anyone to see. The code can be audited by anyone to ensure there are fewer security threats.

- How are package managers similar to app stores (such as Apple's App Store, Google Play Store, Microsoft Store, etc.), from a cybersecurity perspective?

App stores employ encryption to accept only software or code that is signed by authorized developers. The operating systems can ensure that only authorized, signed software is being installed. Package managers adopt a similar signing mechanism to ensure that what you download from third parties is trustworthy.

- What threat does use of Content-Security-Policy fields in our source code help to defend against?

XSS Attack

- Provide a specific example of a situation when you might want to use the HTTP POST method instead of the HTTP GET method.

When you want to post your credit card information or your password to a server.

- More precisely known as CVE-2014-0160 but better known as Heartbleed, the discovery of this exploit caused quite an internet panic in 2014, resulting in one of the first times a bug was actively publicized in mass media outlets, as cybersecurity researchers scrambled to make the public aware of the bug and to encourage rapid download of the fix.
Read up on Heartbleed either via the Wikipedia article linked in the previous paragraph, or via any other research you like (such as this video).
Why was Heartbleed such a threat to a user's security?

The confidential data exposed could includes authentication secrets such as session cookies and passwords, allowing attackers to impersonate a user. Also reveal private keys of compromised parties, which would enable attackers to intercepted communications via man-in-the-middle attacks and decrypt it.
