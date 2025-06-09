pipeline{
agent any
tools{
maven 'maven_home'
}
stages{
stage('Build'){
  steps{
bat 'mvn clean install'
}
}
}
}
