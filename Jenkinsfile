node {
    checkout([
        $class: 'GitSCM',
        branches: 'master',
        extensions: scm.extensions + [[$class: 'CleanCheckout']],
        userRemoteConfigs: [[credentialsId: '6b4562bd-e947-4f59-ab5e-4b3f96d1f519', url: 'https://github.com/sanjanrahman/test-run-terraform-ci']]
    ])
      
    //Build, Test, Stage, Deploy
    [...]
} 

