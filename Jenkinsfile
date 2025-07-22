pipeline{
agent any
stages{
stage('compile'){
steps{
echo "compiled Successfully";
}
}
stage('JUnit'){
steps{
echo "Junit tested successfully";
}
}
stage('quality check'){
steps{
echo "Quality check done successfullly";
}
}
}
post{
always{
echo "it always runs"
}
success{
echo "it runs only on success"
}
failure{
echo "it runs on failure"
}
unstable{
echo "it runs when run is unstable"
}
changed{
echo "pipeline chnaged"
}
}
}

