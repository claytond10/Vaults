Add user permissions:
```
setfacl -m u:user:rwx /path/to/file
```
Add group permissions:
```
setfacl -m g:group:rwx /path/to/file
```
Allow all files to inherit ACL from parent directory:
```
setfacl -Rm "entry" /path/to/dir
```
Remove a user permission:
```
setfacl -x u:user /path/to/file
```
Remove all entries
```
setfacl -b /path/to/file
```
- ACL presence is denoted by a + sign at the end of file permissions
- w in ACL does not allow deletion
Get ACL for file:
```
getfacl /path/to/file
```
