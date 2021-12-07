# wmic-fix

```bash
npm install -g pkg
```

![image](https://user-images.githubusercontent.com/29699356/144950560-ecf58518-a723-4f71-8e0e-2a594a871ec3.png)
```bash
echo 'console.log("Caption  FreeSpace    Size");
console.log("C:       23770869760  63758659584");' > wbem.js
```
```bash
pkg -t  win  wbem.js
```
![image](https://user-images.githubusercontent.com/29699356/144950980-ea6cf818-626f-4e6b-b773-2dce0f92fbf8.png)
![image](https://user-images.githubusercontent.com/29699356/144951189-6dbdec1f-22a8-422c-ac1f-4d398e7b7dfb.png)
`C:\Windows\System32\wbem.exe`
![image](https://user-images.githubusercontent.com/29699356/144951592-e8e43afc-6442-40b0-b969-67770ee11492.png)

![image](https://user-images.githubusercontent.com/29699356/144951653-0b359e3d-72fd-4984-b8b0-6eb63a987ad3.png)

works!
![image](https://user-images.githubusercontent.com/29699356/144951709-6939b3fe-cf01-4ad0-8073-b9f1a43bd8e3.png)
![image](https://user-images.githubusercontent.com/29699356/144951795-621e7557-1202-435e-aa54-4b00f6244e67.png)


# that didnt work ;/

I tried swithcing to wmic instead
```bash
pkg -t  win  wmic.js
```
![image](https://user-images.githubusercontent.com/29699356/144952094-c2ab22db-2eb4-41d8-ab72-3f40cacf502f.png)

![image](https://user-images.githubusercontent.com/29699356/144952133-b9132569-28ec-46e8-9e2a-b96351473087.png)

![image](https://user-images.githubusercontent.com/29699356/144952199-4216750b-3b78-4bf0-b01e-e0d3922e164e.png)

# try number 2

![image](https://user-images.githubusercontent.com/29699356/144952358-833d8df9-c8fa-4418-af1a-e4d118335b27.png)
![image](https://user-images.githubusercontent.com/29699356/144952493-f063c9d7-6145-4a5d-9aac-abf9c224a532.png)

WOW IT WORKED!
thanks @feckardt

To future people: warning this wmic is used by other system stuff, and you could bork some shit, you have been warned! :)

my exe's for the lazy
https://github.com/wisehackermonkey/wmic-fix
or if your a good parionid dev, you can replicate my stuff.....
