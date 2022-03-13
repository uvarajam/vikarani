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
         sshagent(credentials:[''])
         sh 'ssh -o StrictHostkeyGhecking=no root@192.168.112.132  uptime'
         sh 'ssh -v root@192.168.112.132'
         /sh 'scp '.\workspace\pipeline root@192.168.112.132:/root/vika/yuva
     }
 }
