# backrest-playground [work in progress]
### What is this? 
It's an environtment based on 2 Postgres virtual machines and 1 Pgbackrest conected to this clusters in order to do backup, restore and demostrate some capabilities of this great backup tool.   


to play with pgbackrest backups and restores. 
We are using Vagrant to create environtment, as follow: 

### How to use it? 

1. Download repository on your computer
```
git clone https://github.com/andreleox/backrest-playground
```
2. Use vagrant to start environtment
```
vagrant up
```
3. Show status of your environment
```
vagrant status
```
4. Show status of your environment
```
vagrant ssh backrest1
sudo su - backrest 
```
