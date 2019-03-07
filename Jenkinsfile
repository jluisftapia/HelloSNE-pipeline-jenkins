node{
	
	stage('SCM Checkout'){
	git 'https://github.com/jluisftapia/HelloSNE-pipeline-jenkins
	}
	stage('Compile-Package'){
		sh 'mvn package'
	}
}
