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

sh 'java -jar /Users/admin/Desktop/cd-docker-ansible/mkYong/spring-boot-web-jsp/spring-boot-web-jsp-1.0.war >/dev/null 2>&1 &'
}
}


}
}
