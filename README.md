# ssh-key-mgt
Keep my authorized_keys file containing FIDO2 backed public keys up-to-date on many linux machines.


Define steps of the mechanism:
1. Keep the main authorized_keys file in this repo
2. How do Linux machines autheticate to this repo?
3. Automate the sync if a change to authorized-keys file is made
  a. Distribute the script that sync's the file
  b. Use cron or another mechanism to trigger the sync?
