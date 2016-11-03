# Meetup demo - Ansible in a container era

For this demo with used GKE on Google Cloud Plateform.

(slides here)[https://speakerdeck.com/yanc0/ansible-in-a-container-era#]

## Install (in a virtualenv)

```
pip install -r requirements.txt

# build new environment
ansible-conainter build

# launch dev containers
ansible-conainter run

# build prod ready images
ansible-conainter build

# push it to registry
ansible-conainter push --push-to google 

# generate deployment configuration
ansible-conainter shipit --pull-from google

cd ansible

# deploy
ansible-playbook shipit-kubernetes.yml
```

## Contributing / Support

We will not maintain this repo, archiving purpose only
