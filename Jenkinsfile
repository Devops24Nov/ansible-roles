
node("ansible-label"){

stage("download"){
 git "https://github.com/quickfixtech/ansible-roles"
}
stage("role download){
 ansible-galaxy install -r requirement.yml
}
stage("run playbooks"){
ansible-playbook -i hosts site.yml
}

}
