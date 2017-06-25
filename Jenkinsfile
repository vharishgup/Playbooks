pipeline {
agent any
stages {
stage('build') {
steps {
sh 'ansible local -m ping'
sh 'ansible-playbook loop.yml'
}
}
}
}
