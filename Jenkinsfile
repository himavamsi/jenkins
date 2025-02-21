pipeline{
    
    agent any
    
    paraeters{
        
        choice(name:"cloud", choices:["AWS","GCP","Azure"], description:"The cloud  which we are going to use")
        choice(name:"environment", choices: ["Dev","Test","Prod"],description: "The  environment where we are going to provision machines")
    }
    
    stages{
        
        stage{
            
            steps{
                echo "The cloud is ${params.cloud} and environment is ${environment}"
        }
    }
}
