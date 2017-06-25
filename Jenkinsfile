pipeline {
agent any
stages {
stage('build') {
steps {
sh 'id'
sh 'sudo su ansible'
sh 'ansible-playbook loop.yml'
}
}
}
}
