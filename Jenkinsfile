pipeline {
agent any

```
stages {

    stage('Clone Repository') {
        steps {
            echo "Cloning GitHub repository..."
            git branch: 'main', url: 'https://github.com/radhikaraut/myproject.git'
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
    success {
        echo "Pipeline executed successfully!"
    }
    failure {
        echo "Pipeline failed!"
    }
}
```

}
