pipeline{
    agent any
stages {

stage('Checkout'){
steps{
git 'https://github.com/dsrdsr8/spring-boot-web-jsp.git'
}
}

stage('Build'){
steps{
sh 'mvn clean package'
}
}

stage('Deploy'){
steps{
input 'Do you approve the Deployment ?'
		echo 'Deploying...............' 

}
}


}
}
