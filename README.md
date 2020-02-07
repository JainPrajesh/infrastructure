# CSYE 7374 - Spring 2020

## Team Information

| Name | NEU ID | Email Address |
| --- | --- | --- |
|Jagmandeep Kaur | 001426439|kaur.j@husky.neu.edu |  | | |
|Mayank Barua| 001475187| barua.m@husky.neu.edu|
|Yogita Patil| 001435442|patil.yo@husky.neu.edu |
|Prajesh Jain| 001409343| Jain.pra@husky.neu.edu|

## Run Ansible Playbook

Open terminal and run the ```ansible-playbook``` command in the below format with parameters

To create the AWS infrastructure run following

```bash
$ ansible-playbook -i hosts-v site.yml --tags create --extra-vars "hosted_zone=value jenkins_subDomain=value certbot_email=value restart=true/false"
```

To delete the AWS infrastructure run following

```bash
$ ansible-playbook -i hosts-v site.yml --tags delete --extra-vars "key=value value=value"
```

