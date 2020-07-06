# sam-cli-learning

## useful links
* https://alexharv074.github.io/2019/03/02/introduction-to-sam-part-i-using-the-sam-cli.html
* https://alexharv074.github.io/2019/03/02/introduction-to-sam-part-ii-template-and-architecture.html

## userful commands
* sam local invoke <ResourceFunctionName> --event event.json
* sam build
  * builds are saved in .aws-sam/build
  * everytime you change the code you have to rebuild for both local testing and deploying latest code
  * sam build --use-container does a build in a container. not sure what the defaault mode is, todo look this up.
* sam validate --template template.yaml
* sam deploy --template-file packaged.yaml --stack-name HelloWorld --capabilities CAPABILITY_IAM
