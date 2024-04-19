pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building the HTML file...'
                sh 'echo "<!DOCTYPE html>" > index.html'
                sh 'echo "<html>" >> index.html'
                sh 'echo "<head>" >> index.html'
                sh 'echo "    <title>First Web Page</title>" >> index.html'
                sh 'echo "</head>" >> index.html'
                sh 'echo "<body>" >> index.html'
                sh 'echo "   <h1 style=\'color: violet; font-size: 40px;\'>Hello, Welcome to my World!</h1>" >> index.html'
                sh 'echo "   <h2 style=\'color:Orange; font-size: 30px;\'>This is Preethi\'s first web app!</h2>" >> index.html'
                sh 'echo "   <h3 style=\'color:Blue; font-size: 30px;\'>I Love Roni ponki and Niha tunki:)</h3>" >> index.html'
                sh 'echo "</body>" >> index.html'
                sh 'echo "</html>" >> index.html'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying the HTML file...'
                // Add your deployment steps here
            }
        }
    }
}
