pipeline {
  agent any
  stages {
    stage('Inicio') {
      agent any
      steps {
        echo 'B1'
      }
    }
    stage('paso2') {
      steps {
        mail(subject: 'Prueba', body: 'prueba jenkins', from: 'juan.calderon@aldeamo.com', to: 'juan.calderon@aldeamo.com')
      }
    }
  }
}