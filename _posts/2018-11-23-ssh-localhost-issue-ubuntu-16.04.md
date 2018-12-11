---
layout: post
title: SSH localhost issue on Ubuntu 16.04 
tags: [hadoop, ssh, ubuntu16.04]
---

SSH localhost issue on Ubuntu 16.04 

Recently I installed ubuntu 16.04 for my Hadoop work. Running hadoop asks you enter password 3 times. to the disabled password from entering multiple times, I was using ssh like below -

ssh localhost
ssh-keygen -t dsa -P '' -f ~/.ssh/id_dsa 
cat ~/.ssh/id_dsa.pub >> ~/.ssh/authorized_keys

but it was not working.

Problem was, 

DSA keys are not accepted in recent versions of OpenSSH by default. You should use RSA. If you really want to use DSA keys, you should add

PubkeyAcceptedKeyTypes ssh-dss line into your sshd_config and restart ssh service.

what i did in order to make it work.

First  delete ~/.ssh folder and then run the above command with rsa algo.
