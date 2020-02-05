pipeline{
agent any
stages{

stage('Jenkins job'){
 steps {
 sh '''
 curl -X GET \
  http://ec2-18-191-16-16.us-east-2.compute.amazonaws.com:8080/rest/api/2/project \
  -H 'accept: application/json' \
  -H 'authorization: Basic cmlnOmRpZ2l0YWxyaWdAMTIz' \
  -H 'cache-control: no-cache' \
  -H 'postman-token: 01555e16-0c68-d312-c858-4411b4d1a40e'
 '''
 }
 }
 }
 }
