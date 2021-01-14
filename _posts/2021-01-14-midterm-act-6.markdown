---
layout: post
categories: jekyll update
title:  "MIDTERM-ACT-6"
---

![104281202-16681d80-54e8-11eb-9078-1ef278217c83](https://user-images.githubusercontent.com/75325962/104575255-ea889b80-5691-11eb-9cff-aff07244d103.png)

1. Fork this repository [https://github.com/ajcanlas-tip/sysad2-12021.git](https://github.com/ajcanlas-tip/sysad2-12021.git)

2. Clone your newly forked repository.

3. Make a new branch named "activity6" from master branch using *git branch activity6* and *git checkout activity6*

4. Make a new new remote upstream with git remote add upstream  [https://github.com/ajcanlas-tip/sysad2-12021.git](https://github.com/ajcanlas-tip/sysad2-12021.git)

5. Create a playbook that installs dhcpd, bind9, vsftpd, samba, httpd, mariadb in both Ubuntu and Centos (use Roles to optimize the playbook)

6. Create different plays in installing per service and identify it as a group in Inventory file.

7. add,commit and push it to your activity6 branch

8. Request a pull request for the master branch in [https://github.com/ajcanlas-tip/sysad2-12021.git](https://github.com/ajcanlas-tip/sysad2-12021.git)  and activity6 branch of your forked repository.

### SUMMARIZATION OUTPU:

Git branch link: [https://github.com/qjaaferrer/sysad2-12021/tree/activity6](https://github.com/qjaaferrer/sysad2-12021/tree/activity6)

```
.
 1810135
  activity6
      README.md
      ansible.cfg
      inventory
      playbook.yaml
      roles
          centos_installation
           README.md
           defaults
            main.yml
           handlers
            main.yml
           meta
            main.yml
           tasks
            main.yml
           tests
            inventory
            test.yml
           vars
               main.yml
          ubuntu_installation
              README.md
              defaults
               main.yml
              handlers
               main.yml
              meta
               main.yml
              tasks
               main.yml
              tests
               inventory
               test.yml
              vars
                  main.yml
 README.md

```
