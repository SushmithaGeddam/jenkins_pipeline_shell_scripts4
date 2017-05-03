node {
   
   	stage 'Stage 1'
   		echo 'Hello there, shell scripts'
   	stage 'Checkout'
   		git url: 'https://github.com/SushmithaGeddam/jenkins_pipeline_shell_scripts4.git'
   	stage 'Build'
   		sh './myBuild.sh'
   	stage 'Deploy'
   		sh './myDeployment.sh'
  
}