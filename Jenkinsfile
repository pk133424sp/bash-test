node {
    sh 'ls -l'
    dir ('test-1') {
        writeFile file:"sample1.txt", text:"this is first writte"
    }
    sh 'ls -l'
    dir ('foo'){
        deleteDir()
    }
    sh 'cd test-1'
    sh 'ls -l'
    sh 'rm -rf sample1.txt'
     sh 'ls -l'
   
}
