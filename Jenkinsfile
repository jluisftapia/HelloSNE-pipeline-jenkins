node{
	
	stage('SCM Checkout'){
	git 'https://github.com/javahometech/my-app'
	}
	stage('Compile-Package'){
		def mvnHome = tool name: 'maven_3_6_0', type: 'maven'
		sh "${mvnHome}/bin/mvn package"
	}
}
