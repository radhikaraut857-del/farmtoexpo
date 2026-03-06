pipeline {
agent any

```
stages {

    stage('Checkout Code') {
        steps {
            echo "Cloning the repository..."
            checkout scm
        }
    }

    stage('Build') {
        steps {
            echo "Building the project..."
        }
    }

    stage('Test') {
        steps {
            echo "Running tests..."
        }
    }

    stage('Deploy') {
        steps {
            echo "Deploying application..."
        }
    }
}

post {
    always {
        echo "Pipeline execution completed."
    }
    success {
        echo "Build was successful."
    }
    failure {
        echo "Build failed."
    }
}
```

}
