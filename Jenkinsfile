// Powered by Infostretch 

timestamps {

node () {

	stage ('python-satya - Checkout') {
 	 checkout([$class: 'GitSCM', branches: [[name: '*/main']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: '863fc837-9843-41fc-a867-2845cff1e42a', url: 'https://github.com/sathyanarayanakalleti/python-dev-ec2.git']]]) 
	}
	stage ('python-satya - Build') {
 			// Shell build step
sh """ 
sudo service apache2 start 
 """ 
	}
}
}