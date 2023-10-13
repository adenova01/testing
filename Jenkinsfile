pipeline {
    agent{
        label "default"
    }
    stages{
        stage('Pull master branch') {
            when{
                branch "main"
            }
            steps {
                bat("whoami")
                bat("dir")
                dir('C:/Users/adeno/OneDrive/Dokumen/CrossTechno/rnd/CICD/testing') {
                    bat("git config remote.origin.url")
                    bat("git pull https://adenova01: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@github.com/adenova01/testing")
                }
            }
        }
    }
}