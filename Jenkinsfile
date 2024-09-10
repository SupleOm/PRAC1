pipeline{
agent any
stages{
stage('checkout'){
steps{
git 'https://github.com/SupleOm/PRAC1.git'
}}
stage('build'){
steps{
sh 'mvn install'
}}
stage(deploy){
steps{
 sh 'cp target/PRAC1.war /home/omsuple/Devopstool/apache-tomcat-9.0.93/webapps/'
}}
}
}
