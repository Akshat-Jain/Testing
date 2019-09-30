### An SSH key is an access credential in the SSH protocol.
### Its function is similar to that of user names and passwords, but the keys are primarily used for automated processes and for implementing single sign-on by system administrators and power users.


#### HOW TO SET UP PUBLIC KEY AUTHENTICATION FOR OPENSSH :-
##### SSH keys are typically configured in an authorized_keys file in .ssh subdirectory in the user's home directory. Typically a system administrator would first create a key using ssh-keygen and then install it as an authorized key on a server using the ssh-copy-id tool. See also the dedicated page on configuring authorized keys for OpenSSH.
##### We recommend using passphrases for all identity keys used for interactive access. In principle we recommend using passphrases for automated access as well, but this is often not practical.

