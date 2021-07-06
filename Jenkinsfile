@Library('shared-library') import com.dai.MyPipeline
// import com.dai.test


// def mytest = new test()

// pipeline {
//     agent any
//     stages{
//         stage("Run factory for statemachine"){
//             when{
//                 expression {mytest.foo("ci")}
//             }
//             steps{
//                 echo "cistateMachine function will work!"
//             }
//         }
//     }
// }

agent any
// instantiate
def pl = new MyPipeline(this)

pl.foo()