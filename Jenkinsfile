pipeline {
agent any
stages {
stage('build') {
steps {
sh 'su ansible'
sh 'ansible-playbook loop.yml'
}
}
}
}
