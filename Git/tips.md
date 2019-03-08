# Tips
## Cannot push to new Repository using other account
- MacOS might use KeyChainAccess.app to save your account info
- delete github.com from KeyChainAccess.app
- After that you can push to your repository (git would ask you your name and password)
- reference
    - https://qiita.com/s5601026/items/54304bbdaf025ef8f8bb
- It will still happen again when you push next time
- You have to remove git config credential.helper from your git config
- reference
    - https://qiita.com/euxn23/items/28d10bf9e0610bb54bbe
- you have to change the permission of git config when you rewrite Xcode's git config
- so you won't get error anymore. But at the same time you have to input your account name and password every time. 
- This would not be suggested for the user who does not switch account often.

## How to untrack a file in git
1. Move the file to other directory
1. Add the file name you delete to git ignore
1. Move back the file to original directory