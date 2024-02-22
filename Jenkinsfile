pipeline{
    agent any 
    stages{
        stage('Git Checkout'){
            steps{
                gitCheckout{
                    branch: "main",
                    url: "https://github.com/TechnoAhmed/java_app_ahmed.git"
                }
            }
        }
    }
}