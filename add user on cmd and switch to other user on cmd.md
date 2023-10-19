## Add User
```
net user nameyouwant password /add
net localgroup administrators nameyouwant /add
```
---
## Switch CMD To Any User
**computer_name**&nbsp;: `hostname` <br>
**your_username**&nbsp;: `net user`
```
runas /user:computer_name\your_username cmd.exe
```
`echo %username%`
