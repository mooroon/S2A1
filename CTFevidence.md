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

