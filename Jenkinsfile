pipeline {
agent any
stages {
stage('build') {
steps {
sh 'apt-get install -y ansible'
sh 'mv /etc/ansible/hosts /etc/ansible/hosts.org'
sh 'echo "[local]" > /etc/ansible/hosts'
sh 'echo "172.31.103.71" >> /etc/ansible/hosts'
sh 'ansible-playbook loop.yml'
}
}
}
}
