src = "/home/pulse-02/users.json"
des = "/home/pulse-02/Desktop/Learning"

node 
{
   sh 'ls -l'
    dir ('test-1') {
        writeFile file:"sample1.txt", text:"this is first writte"
    sh 'ls'
       sh 'rm -rf sample1'
       sh 'cp -rf "$src" "$des"'
    } 


}

