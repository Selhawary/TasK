node {
    stage('Clone Repository') {
        git credentialsId: 'git-ssh-key', url: 'https://github.com/mahmoud254/Booster_CI_CD_Project', branch: 'master'
    }
    stage('List Files') {
        sh 'ls'
    }
}
