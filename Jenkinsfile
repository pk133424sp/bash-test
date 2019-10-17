

node 
{
   
   sh 'ls -l'
    dir ('test-1') {
        writeFile file:"sample1.txt", text:"this is first writte"
    sh 'ls'
       sh 'rm -rf sample1'
       
       sh 'mv  sample1.txt /var/lib/jenkins/'
       sh 'ls'
       } 


}

