A beginner tester writes:

✅ Valid username

✅ Valid password

Done.

A senior tester asks:

Empty username?
Empty password?
Both empty?
Only spaces?
SQL injection?
XSS payload?
500-character password?
Emojis?
Unicode?
Copy-paste?
Auto-fill?
Password visibility toggle?
Caps Lock?
Multiple failed attempts?
Account lock?
Disabled user?
Deleted user?
Expired password?
Session timeout?
Browser Back?
Concurrent logins?
Slow internet?
Mobile browser?
Accessibility (keyboard-only navigation, screen readers)?

Same feature.

Completely different depth.


###  question to ask senior QA before touching application

Imagine you're in a meeting.

Instead of asking

Can I test everything?

Ask questions like these.

## Functional Questions

Should users login using

Email only?
Username?
Phone Number?

# Can email be

ABC@gmail.com

or

abc@gmail.com


Should both work?

# Is password

Case-sensitive?

Minimum password length?

Maximum password length?

Can password contain spaces?

Can password contain emojis?

Can password contain Unicode?

What happens after 5 failed login attempts?

Should account lock?

For how long?

Can deleted users login?

Can inactive users login?

What happens after successful login?

Dashboard?

Homepage?

Previous page?

# Remember Me...

Should it store

Only email?

Or email + password?

Or authentication token?

How long should it remember?

# Forgot Password

OTP?

Email Link?

Security Questions?

Expiration time?

 # Session

Should login expire?

After

15 minutes?

30 minutes?

24 hours?

# Multiple Devices

Can same account login

from two devices?

Can same account login

from ten devices?

Should old sessions expire?

# Browser

Supported browsers?

Chrome?

Firefox?

Safari?

Mobile?

Accessibility

Keyboard only?

Screen reader?

High contrast?

# Security

Rate limiting?

Captcha?

Brute force protection?

CSRF?

HTTPS only?

Now compare this with your question.

You asked

Is backend integrated?

I ask nearly 30 requirement questions before touching the application.

That's how senior QAs avoid misunderstandings.