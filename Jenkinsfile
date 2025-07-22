pipeline{
    agent any
    stages{
        stage('compile'){
            steps{
                echo"Compiled successfully";
            }
        }
    stage('Junit'){
        steps{
            echo"JUnit test passedSuccessfully";
    }
}
stage('Qualitycheck'){
    steps{
        echo"Quality Check passed successfully";
    }
}
stage('Deploy'){
    steps{
        echo"Deployed Successfully";
    }
}
}
post{
    always{
        echo"This will always run"
    }
    success{
        echo"This will run on success"
    }
    failure{
        echo"This will run on failure"
    }
    unstable{
        echo "This will run only if the run is marked as Unstable"
    }
    changed{
        echo"Pipe line changed"
    }
}
}
