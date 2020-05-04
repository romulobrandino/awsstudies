# CloudFormation structure

Structure of a template

AWS CloudFormation template

- **Paramenters:** Inputs into template
- **Mappings:** Static variables (typically latest AMIs)
- **Resources:** AWS assests to create
- **Init:** Custom application to run startup
- **WaitCondition:** Signal from instance that user data has completed running
- **Outputs:** Values of custom resources created by template (URLs, usernames, etc)