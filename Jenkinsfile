pipeline{
    agent any
stages {

stage('Checkout'){
steps{
git 'https://github.com/dsrdsr8/git_pet_Clinic.git'
}
}

stage('Build'){
steps{
sh 'mvn spring-boot:run'
}
}

}
}
