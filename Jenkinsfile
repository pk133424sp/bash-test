node {
    sh 'ls -l'
    dir ('test-1') {
        writeFile file:"sample1.txt", text:"this is first writte"
    }
    sh 'cd test-1'
    sh 'ls'
    sh 'rm -rf sample1.txt'
     
   
}
