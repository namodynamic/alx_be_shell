# Shell Permissions 


## <ins>Tasks</ins>
`0-iam_betty:`  A script that switches the current user to user betty
```bash
su betty
```
`1-who_am_i:` A script that prints the effective username of the current user.
```bash
whoami
```
`4-empty:` A script that creates an empty file called `hello`
```bash
touch hello
```
`5-execute:` A  script that adds execute permission to the owner of the file `hello`.
```bash
chmod u+x hello 
```
` 6-multiple_permissions:` A script that adds execute permission to the owner and group owner, and read permission to other users, to the file `hello`.
```bash
chmod u+x,g+x,o+r hello 
```
`9-John_Doe:` A script that sets the mode of the file hello to this: `-rwxr-x-wx`
```bash
chmod 753 hello
```