# PGBackrest Playground [work in progress]
### What is this? 
It's a Pgbackrest environment conected with 2 Postgres clusters (VM) in order to demostrate some capabilities of this great backup tool, like backup, delta restore, diferencial backups and so on. 

### Pre-requisites: 
* Vagrant shuld be installed on you machine
* Virtualization tool like Virtualbox, Hyperv

![Mindmap](https://github.com/andreleox/backrest-playground/blob/master/playground-architecture.png)

### How to use it? 

1. Download repository on your computer
```
git clone https://github.com/andreleox/backrest-playground
cd backrest-playground
```
2. Use vagrant to start environtment
```
vagrant up
```
3. Show status of your environment
```
vagrant status
```
4. Acessing pgbackrest virtual machine
```
vagrant ssh backrest1
sudo su - backrest 
```

### Basics 

![Mindmap](https://github.com/andreleox/backrest-playground/blob/master/backrest.png)
