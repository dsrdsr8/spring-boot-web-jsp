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
sh 'mvn package'
}
}

stage('Deploy'){
steps{
input 'Do you approve the Deployment ?'
		echo 'Deploying...............' 

sh "'nohup java -jar /Users/admin/.jenkins/workspace/mkYong_weProj/target/spring-boot-web-jsp-1.0.war &'"

}
}


}
}
