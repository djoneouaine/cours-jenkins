node {
    stage('build and run') {
        git branch: 'main', credentialsId: 'djoneouaine', url: 'https://github.com/djoneouaine/cours-jenkins.git'
        sh 'chmod 777 hello-world'
        sh './hello-world'    
        }}
