node {
  stage('Greeting') {
    echo 'Starting greeting'
    
    for (int i = 1; i <= 5; i++) {
      echo "Hello, User ${i}!"
    }
    
    echo 'Finishing greeting'
  }
  
  stage('Numbers') {
    echo 'Starting numbers'
    
    for (int i = 1; i <= 10; i++) {
      if (i % 2 == 0) {
        echo "${i} is even"
      } else {
        echo "${i} is odd"
      }
    }
    
    echo 'Finishing numbers'
  }
}
