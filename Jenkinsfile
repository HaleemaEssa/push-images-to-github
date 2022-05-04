pipeline {
       
    stages {
                
    stage('PushImage') {
         
            steps {
              //sh "git checkout main"
              sh "git add /home/haleema/output.png"
              sh "git commit -m 'output image'"
              sh "git remote add origin https://github.com/HaleemaEssa/push-images-to-github.git"
              sh "git push -u origin main"      
                
            }
         }    
    
   
    }
}
