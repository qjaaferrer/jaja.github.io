---
layout: post
categories: jekyll update
title:  "MIDTERM EXAM: Hands-On"
---

![104281202-16681d80-54e8-11eb-9078-1ef278217c83](https://user-images.githubusercontent.com/75325962/104575255-ea889b80-5691-11eb-9cff-aff07244d103.png)

## PROCEDURE

1. Fork this repository [https://github.com/ajcanlas-tip/sysad2-12021.git](https://github.com/ajcanlas-tip/sysad2-12021.git)

2. Clone your new repository in your VM *https://github.com/< your username >/sysad2-12021.git*

3. Create a branch named "midterm-exam" and checkout in that branch.

4. Create an Ansible playbook that does the following with an input of a config.yaml file and arranged Inventory file:

	 4.1 Install and configure Elastic Stack in separate  hosts (Elastic Search, Kibana, Logstash)

	 4.2 Install Nagios in one host

	 4.3 Install Grafana,Prometheus and Influxdb in seperate hosts (Influxdb,Grafana,Prometheus)

	 4.4 Install Lamp Stack in seperate hosts (Httpd + Php,Mariadb)

5. push and commit your midterm-exam branch in the VM (no need for ansible.cfg upon pushing)

6. request a pull request from that branch in GitHub

7. For your midterm exam to be counted, please paste your repository link as an answer in this exam.


### SUMMARIZATION PATH:

Git branch link: [https://github.com/qjaaferrer/sysad2-12021/tree/midterm-exam](https://github.com/qjaaferrer/sysad2-12021/tree/midterm-exam)

```
.
 README.md
 config.yaml
 grafana.repo
 influxdb.repo
 inventory
 main.yaml
 roles
     elk_ubuntu
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
     grafana_host
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
     httpd_host
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
     influxdb_host
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
     kibana_host
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
     logstash_host
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
     mariadb_host
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
     nagios_host
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
     prometheus_host
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
```
