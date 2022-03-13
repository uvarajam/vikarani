pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
    }
}
Stage('ssh deploy')
 {
     steps
     {
         sshagent(credentials:['cr'])
         sh 'ssh -o StrictHostkeyGhecking=no root@192.168.112.132  uptime'
         
     }
 }
