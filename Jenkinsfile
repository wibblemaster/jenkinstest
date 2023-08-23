node('jenkins-slave') {
    
     stage('test pipeline') {
        sh(script: """
           echo "hello"
           git clone https://github.com/wibblemaster/jenkinstest.git
           cd ./jenkinstest
           
           echo "Got this far!"
        """)
    }
}
