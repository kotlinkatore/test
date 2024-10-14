# test


Run
```shell
  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"
```
```shell
abhijeetkatore@cloudshell:~/test (abhijeet-katore)$ git config --global user.email "you@example.com"
abhijeetkatore@cloudshell:~/test (abhijeet-katore)$ git config --global user.name "username"
abhijeetkatore@cloudshell:~/test (abhijeet-katore)$ git commit -m "Created first workflow"
[main a7e90d8] Created first workflow
 1 file changed, 14 insertions(+)
 create mode 100644 .github/workflows/first-workflow.yml
abhijeetkatore@cloudshell:~/test (abhijeet-katore)$ git push origin main
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 2 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (5/5), 553 bytes | 553.00 KiB/s, done.
Total 5 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/kotlinkatore/test.git
   7561ce4..a7e90d8  main -> main
```
```shell
git clone <>
cd <>
```
```
cloudshell workspace .
```

```yml
name: first workflow
on: push

jobs:
  run-script:
    runs-on: ubuntu-latest
    steps:
      - name: echo a name
        run: echo "I am from Github Actions"
      - name: multiline script
        run: |-
          echo "Printing versions of npm and node"
          node -v
          npm -v 
```
        
![image](https://github.com/user-attachments/assets/2b1c06fa-5258-4dcb-a493-f0b106b29d76)


![image](https://github.com/user-attachments/assets/4a3ef387-4c29-49b1-8478-bb9246a2d630)
