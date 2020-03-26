pipeline {
     agent any
     parameters{
        string(defaultValue: 'master', description: 'branch name', name: 'branch_Name')
     
}
     stages{

         stage('cleanWorkspace'){
            steps{
                step([$class: 'WsCleanup'])
}
}
         stage('clone'){
              steps{
                 git branch: "${params.branch_Name}"
                 credentialsId: 'test'
                 url: 'https://github.com/dev-lx/parameter.git'

}




}

}





}
