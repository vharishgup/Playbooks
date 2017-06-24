pipeline {
agent any
stages {
stage('build') {
steps {
sh 'apt-get install -y ansible'
sh 'ansible-playbook loop.yml'
}
}
}
}
