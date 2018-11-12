parallel 'test':
{
    node {
    stage "Sample pgm"
    echo 'Hello World'
    writeFile file: "output/usefulfile.txt", text: "This file is useful, need to archive it."
    stage "Sample pgm"
    echo 'Hello World'
}
},'ftest':{

 node {
    stage "Sample pgm1"
    echo 'Hello World'
    writeFile file: "output/usefulfile.txt", text: "This file is useful, need to archive it."
    stage "Sample pgm1"
    echo 'Hello World'
}
}