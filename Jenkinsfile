node()
{
    checkout([$class: 'GitSCM', branches: [[name: '*/master']],
     userRemoteConfigs: [[url: 'https://tmustain:4aab43392c053cb497302b0c34fe3189621b517b@github.com/tmustain/jenkinstest.git']]])
    
    print "DEBUG: parameter target = ${target}"
    print "DEBUG: parameter build = ${build}"
}


