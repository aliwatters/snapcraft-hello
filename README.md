# Experimenting with snap builds and github actions

[See verbose notes here](https://github.com/aliwatters/sandbox/tree/main/2021/github-actions)

Generated token with

```
ali@stinky:~/git/snapcraft-hello (main)$ snapcraft export-login --snaps=aliwatters-hello    --acls package_access,package_push,package_update,package_release       exported.txt
Enter your Ubuntu One e-mail address and password.
If you do not have an Ubuntu One account, you can create one at https://snapcraft.io/account
Email: ali.watters@gmail.com
Password:

We strongly recommend enabling multi-factor authentication: https://help.ubuntu.com/community/SSO/FAQs/2FA

Login successfully exported to 'exported.txt'. This can now be used with

    snapcraft login --with exported.txt

to log in to this account with no password and have these
capabilities:

snaps:       ['aliwatters-hello']
channels:    No restriction
permissions: ['package_access', 'package_push', 'package_update', 'package_release']
expires:     2022-01-31T16:07:15.586639

This exported login is not encrypted. Do not commit it to version control!
```
