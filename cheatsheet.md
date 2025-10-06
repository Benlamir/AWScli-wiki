# AWS CLI Cheatsheet

aws --versin                          # Shows the installed AWS CLI version to confirm it’s set up.
aws configure                         # Starts an interactive setup to enter your Access Key, Secret Key, Region, and output format.
aws configure list                    # Displays which credentials and config values are currently active.
aws sts get-caller-identity           # Verifies that your credentials work; shows your AWS Account, User, and ARN.
aws iam get-user                      # (Optional) Confirms the IAM user details tied to your credentials.
aws configure set region eu-west-1    # Manually sets a default region without reopening the full configuration prompt.
