# Cost-Management-Operator-On-Z
This is maintaining some cmo-operator-on-z code via GitHub Actions.
All the Github Actions are executed manually and they automate certain tasks on each external, secured repo respective to the repository.
- kvm_workflow<br>
  Builds binary of operator on kvm and pushes that binary as releases in the respective repository
- zvm_workflow<br>
  Builds and Pushes the docker image of operator on ZVM to QUAY
- cmo_monitoring<br>
  Builds and pushes the docker image of CMO Operator to QUAY
  


