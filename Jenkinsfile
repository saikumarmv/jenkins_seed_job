node('master'){
  stages{
    stage('scm_check_out'){
     git branch: main,
         credentialsId: my_creds,
         url: git_url
    }
    stage(''){
     jobdsl targets: dsl_scripts
    }
  }
}

no