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
sh 'mvn spring-boot:run'
}
}

}
}
