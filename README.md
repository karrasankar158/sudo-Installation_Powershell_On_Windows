How to Install sudo from powershell on windows
Step 1: Open Windows Powershell
Step 2: Set Execution Policy
                Set-ExecutionPolicy RemoteSigned -Scope CurrentUser
Step 3: Install scoop
              iex "& {$(irm get.scoop.sh)} -RunAsAdmin"

Step 4: Install sudo command
               scoop install sudo

Step 5: Congrats Sudo installation done check with one basic command
                sudo echo `Welcome!`

