node {
    stage ("scm")
    {
    git 'https://github.com/ghanigreen/maven_demo.git'
    }
    stage ("build")
    {
    bat 'mvn package'
    }    
    stage ("deploy")
    {
        echo "copy file"
        sh 'cp -R "/c/Program Files (x86)/Jenkins/workspace/Jenkinemavendemo/gameoflife-web/target/gameoflife.war" "/c/Program Files/Apache Software Foundation/Tomcat 9.0_Tomcat10/webapps"'
    }

    
    
}
