pipeline {
    agent any

    stages {
       Stage('ssh deploy')
 {
     steps
     {
         sshagent(credentials:['root'])
         sh 'ssh -o StrictHostkeyGhecking=no root@192.168.112.132  uptime'
         
            }
        }
    }
}

