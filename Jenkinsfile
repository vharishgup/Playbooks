pipeline {
agent any
stages {
stage('build') {
steps {
sh 'id'
sh 'su ansible'
sh 'ansible-playbook loop.yml'
}
}
}
}
