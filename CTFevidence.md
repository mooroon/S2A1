# CTF Evidence

## OS.REVISION

### I love cat. I love every kind of cat
```bash
  ssh os_revision000@10.13.37.10
  ls 
  cat secret.flag
```
### hidden attributes
```bash
  ssh os_revision001@10.13.37.10
  ls -a
  cat secret.flag
```
### navigating around
```bash
  ssh os_revision002@10.13.37.10
  ls 
  cd inhere
  ls
  cat secret.flag
```
### why did the file go ot the police?
```bash
  ssh os_revision003@10.13.37.10
  ls 
  cd inhere0
  ls
  file *
  cat flag06
```
### why did the computer feel lost?
```bash
  ssh os_revision004@10.13.37.10
  find -name '*.flag'
  cat ./inhere3/file35.flag
```
### What’s in a name?
```bash
  ssh os_revision005@10.13.37.10
  find -user adam
  cat ./inhere6/file65.flag
```
### Does size count?
```bash
  ssh os_revision006@10.13.37.10
  find -size 33c
  cat ./inhere6/fjEkweorWp
```
### That’s a lot of words
~~~bash
ssh os_revision007@10.13.37.10
ls
cat os.revision.007.flag | grep 'hornstone 
~~~
### What the wget?
```bash
ssh os_revision008@10.13.37.10
Ls
cd Classwork/
ls
wget 10.13.37.10/secret/flag.7z
ls
7za x
7za x secret.flag.7z -p99647cd064647295fb2b3ff0d4904115
ls
cat secret.flag
```
### It is the strings that matter most
```’bash
ssh os_revision009@10.13.37.10
ls
strings secret
./secret 6fa1b41f5a40b34ca707c6d36a231d79
```

## Networking Administration
### Hello Containerlabs
![](https://github.com/mooroon/S2A1/blob/main/hello.png)
### Connect test-server to a router
![](https://github.com/mooroon/S2A1/blob/main/Connect%20test-server%20to%20a%20router.png)
### Two networks; one router
![](https://github.com/mooroon/S2A1/blob/main/Two%20networks%3B%20one%20router.png)

## Challenges
### challenge.000.000
```bash
 ls
 cd
 inhere/
 ls
 ls -a
 cat .secret 
history
```
### challenge.000.001
```bash
ls -a
cat secret.hint 
find / -size +50c -size -60c
cat /lusr/local/share/obsolete_libs/W344gweSDl.flag 
history
```
### challenge.000.002
```bash
 ls -a
 cat secret.flag 
 cat secret.hint 
 cat secret.flag | grep hornstone
 history
```
### challenge .000.003
![](https://github.com/mooroon/S2A1/blob/main/challenge003.png)
### challenge.000.004
![](https://github.com/mooroon/S2A1/blob/main/challenge004.png)
### challenge.000.005
![](https://github.com/mooroon/S2A1/blob/main/Screenshot%20from%202024-08-23%2013-28-11.png)
