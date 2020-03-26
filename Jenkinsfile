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
                 git branch: '${params.name}',
                 credentialsId: 'master-jenkins',
                 url: 'git@github.com:dev-lx/parameter.git'

}




}

}





}
