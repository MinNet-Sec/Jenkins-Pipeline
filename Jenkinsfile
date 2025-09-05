pipeline{
    agent any
    stages{
        stage("build"){
            steps{
                echo "Building..."
            }
            post{
                success{
                    mail to: "sing.a.minahsong@gmail.com",
                    subject: "Build Status Email",
                    body: "Build was successful!"
                }
            }
        }
    }
}
