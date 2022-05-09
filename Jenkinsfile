pipeline {
        agent any

    stages {
                
    stage('PushImage') {
         
            steps {
              sh 'git config --global user.email "haleema_essa@uomosul.edu.iq"'
              sh 'git config --global user.name "HaleemaEssa"'     
              sh "git checkout main"
              git branch: 'main', url: 'https://github.com/HaleemaEssa/push-images-to-github.git'
              sh 'git add .'
              sh 'git commit -m "output image"'
             // sh 'git remote add origin https://github.com/HaleemaEssa/push-images-to-github.git'
              sh 'git push -u origin main'      
//             git add .
// git commit -m "initial commit"
 //git push origin master
   
            }
         }    
    
   
    }
}
