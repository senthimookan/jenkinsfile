node {
    stage ("scm")
    {
    git 'https://github.com/senthimookan/maven_demo.git'
    }
  stage ("build")
   {
    bat "mvn package"
    }    
    stage ("deploy")
    {
        echo "copy file"
 
        bat 'cd "C:/Program Files (x86)/Jenkins/workspace/PipelinedemoJenkinsfilefromscm/gameoflife-web/target"'
        echo "change directory successful"
  //      bat 'cd "C:/Program Files/Apache Software Foundation/Tomcat 9.0/webapps"'
  //      echo "change directory2 successful"
        bat 'copy gameoflife.war "C:/Program Files/Apache Software Foundation/Tomcat 9.0/webapps"'
  //      bat 'copy  "C:/Program Files (x86)/Jenkins/workspace/PipelinedemoJenkinsfilefromscm/gameoflife-web/target/gameoflife.war" . '
        

 //      bat 'copy  "C:/Program Files (x86)/Jenkins/workspace/PipelinedemoJenkinsfilefromscm/gameoflife-web/target/gameoflife.war" "C:/Program Files/Apache Software Foundation/Tomcat 9.0/webapps"'

 //       sh 'cp -R "/C/Program Files/Jenkins/workspace/mavendemo1/gameoflife-web/target/gameoflife.war" "/C/Program Files/Apache Software Foundation/Tomcat 9.0_Tomcat9a/webapps"'
    }

    
    
}
