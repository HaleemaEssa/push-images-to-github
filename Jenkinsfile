pipeline {
        agent {label 'local' }

    stages {
                
    stage('PushImage') {
         
            steps {
               sh 'display ('output.png')'
              sh 'git config --global user.email "haleema_essa@uomosul.edu.iq"'
              sh 'git config --global user.name "HaleemaEssa"'     
              sh "git checkout main"
              //sh 'git remote add origin https://github.com/HaleemaEssa/PushToGithub.git'
              sh 'git remote set-url origin https://github.com/HaleemaEssa/PushToGithub.git'
             // git branch: 'main', url: 'https://github.com/HaleemaEssa/push-images-to-github.git'
              sh 'git init'
              sh 'git add .'
              sh 'git commit -am "initial commit"'
              
              //sh 'git remote add origin https://github.com/HaleemaEssa/PushToGithub.git'
              sh 'git push -u origin main'      
//             // git add .
// git commit -m "initial commit"
 //git push origin master
                    //withCredentials([usernamePassword(credentialsId: 'ci-github', passwordVariable: 'GIT_PASSWORD', usernameVariable: 'GIT_USERNAME')]) {
                        //sh('git push https://${GIT_USERNAME}:${GIT_PASSWORD}@github.com/my-org/my-repo.git')
                   // }
   
            }
         }    
    
   
    }
}
