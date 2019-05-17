node {
    stage ("scm")
    {
    git 'https://github.com/senthimookan/maven_demo.git'
    }
  //  stage ("build")
  //  {
  //  bat 'package'
  //  }    
    stage ("deploy")
    {
        echo "copy file"
        xcopy "C:\Program Files\Jenkins\workspace\mavendemo1\gameoflife-web\target\gameoflife.war" "C\Program Files\Apache Software Foundation\Tomcat 9.0_Tomcat9a\webapps"'
 //       sh 'cp -R "/C/Program Files/Jenkins/workspace/mavendemo1/gameoflife-web/target/gameoflife.war" "/C/Program Files/Apache Software Foundation/Tomcat 9.0_Tomcat9a/webapps"'
    }

    
    
}
