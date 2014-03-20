# Ansible playbook for Selenium

Tested on CentOS 6.5

### Usage
```bash
$ ansible-playbook -i hosts selenium.yml
```
without chromedriver and phantomjs:
```bash
$ ansible-playbook -i hosts selenium.yml --extra-vars "with_chromedriver=false with_phantomjs=false"
```
