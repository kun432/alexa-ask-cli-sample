# alexa-ask-cli-sample

# Usage

1. Setting IAM role for ask-cli

  - Login to AWS
  - Choose IAM
  - Create New Group
    - Name group
      - ex: "ask-cli-group"
    - Choose following policy
      - AWSLambdaFullAccess
      - IAMFullAccess
  - Confirm to create group
  - Create User
    - Name user
      - ex: "ask-cli-user"
    - Choose AWS access type
      - "access by program"
    - Join user to group which created above
    - confirm to create user
  - Download Access Key and Secret Access Key
    - KEEP THESE KEYS SECRET!!!

2. Install ask-cli

```
npm install -g ask-cli
```

git clone https://github.com/kun432/alexa-ask-cli-sample.git
cd alexa-ask-cli-sample
