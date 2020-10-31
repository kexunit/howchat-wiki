## Authentication mechanism

HowChat also has a unique verification mechanism on its unique account mechanism to protect users' privacy.

### Computer (PC side)

Log in for the first time Cooperate with the mobile phone or directly use the computer camera face recognition, and enter the short password to complete the verification. At this time, you can obtain a key to encrypt and store it locally, and extract it when you need to use it.

You don’t need to scan your face again after restarting, just enter the short password (the software lock function can be turned on or not) to open the software and start using.

In order to ensure that you can log in normally even if you lose your phone, you can apply for a scan key after logging in (the scan key is a random verse). The scan key is valid for (1-30) days [custom], and it will become invalid immediately after use. Used to avoid the trouble of first face recognition but no mobile phone.

#### If you log out?

After logging out, you need to log in again for the first time, similar to the mobile terminal.

### Mobile phone (PE side)

When logging in for the first time, directly scan your face and enter the short password to complete the login. If you log out, you need to complete this action again.

### Robot

The robot completes the login via a special API. For details, please see [Robot API](../programme/robotApi.md).