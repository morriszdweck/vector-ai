# vector-ai
Vector is a new upcoming AI Agent- for iOS shortcuts, free to use. it will be able to set timers, send messages and emails, show you where something is ("show me accesibility settings" > opens accesibility deep link.), and do much more that is being decided on. It is currently in early development. Contact @morriszdweck@gmail.com to help in creation.

what models are we using? 
for the AI, we will be giving an option:
Qwen Coder 30B via Pollinations API (free, doesn't require apps, 5k messages available per day for EVERYONE)
ChatGPT app integration.

Because of this, I need github usage daily to upgrade to the flower tier which will allow for 50k messages per day (and maybe acess to better models???) in order to make pollinations the default choice and get rid of ChatGPT integration,as I don't want this to be very confusing. 
Here I will liten to anything you guys have to say, so comment and maybe pitch in.

The AI will use a code-like system to execute multiple tasks at once, so for example it will output code such as:
user: send an email to example@icloud.com and then open the mail app.

MAIL|example@icloud.com|Example title|Example text

URL|message://

QRESPONSE|I've sent the test email and opened the mail app for you, anything else i can help with?

history will sadly not be supported unless someone finds an efficient way to add it.

What we currently need:
- Someone to market (not needed, but best if we do)
- Someone to integrate Search into the shortcut
- Someone to integrate on screen context (via text extraction)
