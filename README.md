**AWS Serverless Application Model Snippets**
--
*These snippets are a direct copy paste of the AWS SAM Template Documentation for easy boiler plate. Custom Snippets will come in future updates.*
[Link to AWS SAM Template Anatomy Definition ](https://docs.aws.amazon.com/serverless-application-model/latest/developerguide/sam-specification-template-anatomy.html)
______________

Simply create a template.yaml file, and in it use the following 
| Template Starter | Description                                                                |
| ---------------- | -------------------------------------------------------------------------- |
| `!samTemplate`   | The Default Anatomy, with the required Transform, and optional properties. |

___
| Global Properties Prefix | Description                                                           |
| ------------------------ | --------------------------------------------------------------------- |
| `GlobalsFunction`        | All the properties available to use with AWS::Serverless::Function    |
| `GlobalsApi`             | All the properties available to use with AWS::Serverless::Api         |
| `GlobalsHttpApi`         | All the properties available to use with AWS::Serverless::HttpApi     |
| `GlobalsSimpleTable`     | All the properties available to use with AWS::Serverless::SimpleTable |

___
| Resources      | Description                                       |
| -------------- | ------------------------------------------------- |
| `ServelessApi` | Creates a logical id, the type and the properties |


