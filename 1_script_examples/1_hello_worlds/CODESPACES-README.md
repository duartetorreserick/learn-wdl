# Testing

## Short instructions 

For testing ```broadinstitute/cromwell``` docker image with Github Codespaces

- start from top, i.e  ```cd /```
- verify java using ```java --version```
- verify cromwell using ```java -jar cromwell.jar --version```
- might have to run ```chmod +x cromwell.jar```
- from this location, i.e. ```root@codespaces_a1db49:/#```, run
- run the following
```
 java -jar ./app/cromwell.jar run ./root/workspace/learn-wdl/1_script_examples/1_hello_worlds/1_hello/hello.wdl
```
- find the output
```
"outputs": {
    "HelloWord.WriteGreeting.output_greeting": "/cromwell-executions/HelloWord/8e519aab-9492-4ca3-947c-6cac6aa1c76a/call-WriteGreeting/execution/stdout"
  },
```