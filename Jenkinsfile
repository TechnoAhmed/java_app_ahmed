pipeline{

    agent any 

    stages{

        stages('Git Checkout'){

            steps{

                script{

                    git branch: 'main', url: 'https://github.com/TechnoAhmed/java_app_ahmed.git'

                }
            }
        }
    }
}