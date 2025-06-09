pipeline{
agent any
tools{
maven 'maven_home'
}
stages{
stage('Build'){
bat 'mvn clean install'
}
}
}
