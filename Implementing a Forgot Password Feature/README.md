# Overview

This pattern generates a new user token, which can be used, alongside a dedicated collection, to enable the forgot password feature.

# Usage

>1. Import ClearBlade and Mailer libraries
>2. Replace `<COLLECTION_NAME>` with the name of a new collection dedicated to storing Tokens
>3. Hard-code admin credentials
>4. Send e-mail with token to user's email

# Further documentation

You can send e-mail with one of the two patterns:
https://github.com/clearblade/ClearBlade-Patterns/tree/master/Sending%20Emails%20with%20Mailer
https://github.com/clearblade/ClearBlade-Patterns/tree/master/Sending%20Emails%20with%20Mailgun