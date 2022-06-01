pipeline {

agent any

stages {

stage('Build') {

steps {

bat 'javac myfile.java'
bat 'java -version'
}

}

stage('Run') {

steps {

bat 'java myfile'
}
}
}
}
