###########################
# Simple Website Template #
###########################

## Install
```
git clone https://github.com/agm1984/simpleWebsiteTemplate.git
cd simpleWebsiteTemplate
npm install
```

## First Run
```
npm start
```

## Test
<http://localhost:3000>

## Contact Form Secrets
This contact form is set up to send the message via email from your localmachine using the module Nodemailer. Visit their website if you want to set it up to email through your Gmail or otherwise.

I am using Fedora 25 with postfix and mailx. If you are using Ubuntu, which you probably are, you should install postfix and mail-utils.

Don't be scared, setting up mail is pretty much a copy paste job with some standard config editing.

I will get you started:

Fedora:
```
dnf install postfix
dnf install mailx
```

Ubuntu:
```
rpm install postfix
rpm install mail-utils
```

Google how to install them. If you choose to set up your contact form using your Gmail as SMTP and your auth credentials, be careful about uploading your code to a GIT Repo. OK? Let's be secure.

Have fun, butcher this badboy up and work your magicks on it.
