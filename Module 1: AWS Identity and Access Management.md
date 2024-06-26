# IAM - Identity and Access Management
## Description
AWS Identity and Access Management (IAM) is a crucial service in AWS that allows you to manage user access and permissions to AWS resources. Understanding IAM is essential for cloud and DevOps professionals as it forms the foundation for security and access control in AWS environments. Proficiency in IAM is highly sought after in job interviews and provides long-term career prospects in cloud security and administration.

## Things to Study

### IAM Users & Groups

### Understand the purpose of IAM users and their role in granting access to AWS resources.
- Learn how to create and manage IAM users through the AWS Management Console, CLI, or SDKs.
- Study the concept of access keys and their usage for programmatic access to AWS services.
- Configure password policies to enforce strong password requirements for IAM users.
- Practice implementing multi-factor authentication (MFA) to add an extra layer of security.

### IAM Roles

- Explore the concept of IAM roles and their benefits in granting permissions to entities within and outside your AWS account.
- Learn how to create and manage IAM roles and define their permissions.
- Understand the process of assuming an IAM role and how temporary security credentials are provided.
- Practice using IAM roles to enable cross-account access and delegation of permissions.

### IAM Policies

- Gain a deep understanding of IAM policies and their role in defining fine-grained access control.
- Study the JSON-based policy language and its elements, including actions, resources, conditions, and effects.
- Practice writing IAM policies to grant or restrict access to specific AWS resources or services.
- Explore the use of policy variables and conditions to create flexible access control rules.

### Single Sign-On (SSO) Identity Center

- Learn about AWS Single Sign-On (SSO) and its benefits in simplifying user management across multiple AWS accounts and applications.
- Understand the process of setting up SSO and configuring federation with external identity providers (IdPs).
- Explore the use of groups and permissions sets in SSO to manage user access effectively.
- Practice integrating SSO with popular identity providers such as Active Directory or SAML-based providers.

### Account Settings

- Familiarize yourself with IAM account settings that enhance security and control.
- Configure and enforce password policies to ensure strong and regularly updated passwords.
- Enable and manage multi-factor authentication (MFA) for IAM users to add an extra layer of protection.
- Explore credential reports to audit and monitor the security of IAM user access.

## Recommended Resources

- AWS IAM User Guide: Official documentation offering in-depth information on IAM concepts, features, and best practices. [Link: https://docs.aws.amazon.com/IAM/latest/UserGuide/ ]
- AWS Identity and Access Management (IAM) Best Practices: Detailed guide providing recommended best practices for IAM configuration and management. [Link: https://aws.amazon.com/iam/docs/iam-best-practices/ ]
- Switching to an IAM role (AW CLI): https://docs.aws.amazon.com/IAM/latest/UserGuide/id_roles_use_switch-role-cli.html   

##Module task
- Create an IAM user with programmatic access and console access.
- Assign a custom IAM policy to the user, granting specific permissions to an S3 bucket.
- Configure multi-factor authentication (MFA) for the user using a virtual MFA device.
- Create an IAM role with the necessary permissions for EC2 instances to access an S3 bucket.
- Test the role by assuming it and accessing an AWS resource.
- Implement a password policy that enforces password complexity and rotation for IAM users.
