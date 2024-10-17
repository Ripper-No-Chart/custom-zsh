# Using Zsh Files

To use a Zsh file, add a `.` at the beginning of the file name. This indicates that it is a hidden file and can be sourced in your terminal.

## File Placement

- Place the Zsh file in your local directory:  
  `/home/username`

## Collaborating on the Project

If you want to collaborate on this project, please let me know! Your contributions are welcome.

## How to Install Zsh

If you don't have Zsh installed, you can follow the instructions at the following link:  
[Installing ZSH](https://github.com/ohmyzsh/ohmyzsh/wiki/Installing-ZSH)

## Technical Details

- This file has been tested on **Ubuntu 24.04.01 LTS**.
- Ensure you have the Zsh shell installed on your system. You can check this by running:

  ```bash
  zsh --version
  ```

## Sourcing the File
- To source the file in your terminal, use the following command:
```
source /home/username/.your_zsh_file
```

## Setting Execute Permissions
- Make sure the file has execute permissions. You can set this with:
```
chmod +x /home/username/.your_zsh_file
```
