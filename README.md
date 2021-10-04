# Jenkins installation using ansible
This ansible playbook will do following task

* Install Jenkins and jenkins plugins
* Create initial user admin:admin
* Install other dependencies on jenkins machine

  - git
  - curl
  - openjdk-8-jdk
  - maven
  - ebcli


# Use

1. Update hosts file with target machine IP and ssh/pem key

2. check and update vars in install-jenkins.yml if needed

3. Run following command to start installation

        ansible-playbook install-jenkins.yml 
