String GHEAccess = 'jenkinsPAT'

library identifier: 'jenkins-sharedlib-my@master', retriever: modernSCM([$class: 'GitSCMSource',
	remote: 'https://github.com/amarlanda/jenkins-sharedlib.git',
	credentialsId: GHEAccess])



evenOrOdd(currentBuild.getNumber())

