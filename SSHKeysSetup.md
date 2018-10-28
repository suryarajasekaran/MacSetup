# SSHKeysSetup

- Generates SSH keys (creates public & private keys)
    ```
    ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
    ```
- The keys are stored in `~/.ssh` folder

    For example :
    ```
    Your identification has been saved in ~/.ssh/id_rsa.
    Your public key has been saved in ~/.ssh/id_rsa.pub. 
    ```
- Provide the public key by running `cat ~/.ssh/id_rsa.pub`, and drop it in other systems like `git` etc.

- **Never** share `~/.ssh/id_rsa` with anyone

