pipeline {
        agent any

    stages {
                
    stage('PushImage') {
         
            steps {
              sh 'git config --global user.email "haleema_essa@uomosul.edu.iq"'
              sh 'git config --global user.name "HaleemaEssa"'     
              sh "git checkout main"
              sh 'git remote set-url origin https://github.com/HaleemaEssa/push-images-to-github.git'
             // git branch: 'main', url: 'https://github.com/HaleemaEssa/push-images-to-github.git'
              sh 'git add .'
              sh 'git commit -m "aaaddd"'
              
             // sh 'git remote add origin https://github.com/HaleemaEssa/push-images-to-github.git'
              sh 'git push -u origin main'      
//             git add .
// git commit -m "initial commit"
 //git push origin master
   
            }
         }    
    
   
    }
}
