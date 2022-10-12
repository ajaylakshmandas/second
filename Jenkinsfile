pipeline {
    agent any
    stages {
        stage('Example') {
            steps {
                echo 'Hello World'

                script {
                    def repo = ['https://github.com/ajaylakshmandas/first.git', 'https://github.com/ajaylakshmandas/second.git']
                    for (int i = 0; i < repo.size(); ++i) {
                        echo "Testing the ${repo[i]} repo"
                    }
                }
            }
        }
    }
}
