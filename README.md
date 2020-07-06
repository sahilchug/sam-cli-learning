# sam-cli-learning

## useful links
* https://alexharv074.github.io/2019/03/02/introduction-to-sam-part-i-using-the-sam-cli.html

## userful commands
* sam local invoke <ResourceFunctionName> --event event.json
* sam build
  * builds are saved in .aws-sam/build
  * evrytime you change the code you have to rebuild for both local testing and deploying latest code
* sam validate --template template.yaml
