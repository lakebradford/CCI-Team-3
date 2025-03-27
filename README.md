# CCI-Team-3

## Setup 

1. Run the command chmod +x setup.sh
2. Then run rclone config
  1. This will ask you to make a new remote, press n and enter.
  2. Name the remote "SDK-folder" and hit enter
  3. For storage, type the number corresponding with Google Drive Storage and hit enter
  4. For client_id and client_secret you can just hit enter
  5. For scope type 1 and hit enter
  6. For root_folder_id and service_account_id hit enter
  7. For Edit advanced config you can type n hit enter
  8. For auto config type y and hit enter
  9. Go to the link provided and authorize rclone access to your google drive
  10. After authorizing, go back to the terminal and type y for "Configure this as a shared drive"
  11. Finally click y and you should see SDK-folder under current remotes
13. Run ./setup. You should see a folder called SDKs appear with all of the SDKs we have obfuscated
    

