node { 
    stage ('git') {
     git 'https://github.com/EnggAdda/JenkinsJobApplication.git'   
    }
    stage ('maven') {
        sh 'mvn package'
    }
}
