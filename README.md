# Mailme
A simple python class help you sending an email easily. I'm recently using this to notify me when my experiment finished.

## Requirements
**Packages**
- install smtplib

## How to use
```python
from mailMe import Mailme

mailme = Mailme(from_addr, password, to_addr, mailbox_name)
"""
    Argument:
        from_addr: mailbox sending mails, eg: 'send@example.com'
        password: your smtp password, eg: 'YOURSMTPPASSWORD'
        to_addr: mailbox receiving mails, eg: 'receive@example.com'
        mailbox_name: now only support(gmail, qqmail, 163mail, outlook)
                      please use '163', 'gmail', 'qq' or 'outlook' as your input
                      
        eg: mailme = Mailme('send@example.com', 'YOURSMTPPASSWORD', 'receive@example.com', 'example')
"""
                
mailme.send_me_text_mail()
```


Now forget your experiment and go grab a cup of coffee ;)
