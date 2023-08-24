pipeline{
    agent ( label 'agent')
    triggers {
        pollSCM('* * * * *')
    }
    stages {
        stage('vcs') {
            steps {
                git url: 'https://github.com/konetipaddu/StudentCoursesRestAPI.git',
                    branch
            }
        }
    }
}