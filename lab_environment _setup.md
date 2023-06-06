## lab environment setup

- Ensure you have an AWS account with the necessary permissions to create and manage CodeBuild resources.
- Create an IAM role for CodeBuild with the required permissions.

      - Open the IAM service in the AWS Management Console.
      - Navigate to "Roles" and click "Create role".
      - Select the CodeBuild use case and proceed with the role creation wizard.

- Set up Open the IAM service in the AWS Management Console.

      - attach the policy for the AWSCodeBuildAdminAccess permission to the role
      - add a tag with a key of "tool" and a value "codebuild" to the role and click on create role
