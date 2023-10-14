node {
    stage('clone repo') {
        git branch: 'main', url: 'https://github.com/asambajava/seliniumJar'
    }
    stage('execute runable jar') {
        sh 'java -jar my-assignment.jar' 
    }
}
