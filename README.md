# ssh-key-mgt
For ssh access to my Linux machines I switched to FIDO2 hardware-token backed ssh keys. I created
this GitHub repository to keep my Public keys stored in the authorized_keys files in sync on all
my Linux machines. Since the Public keys are intended to be publicly available I made this 
repository also public. This also helps the synchronisation scripts on my Linux hosts to simply
copy the 'authorized_keys' file without auhtentication to GitHub.

ToDo:
1. Create some checks or procedures to avoid locking myself out of my Linux machines by copying
   errornous Public keys or otherwise corrupt the 'authorized_keys' file.
