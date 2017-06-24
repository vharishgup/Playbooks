pipeline {
agent any
stages {
stage('build') {
steps {
sh 'apt-get install ansible'
sh 'ansible-playbook loop.yml'
}
}
}
}
