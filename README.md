# aws-sso-role-credentials
Fetch AWS SSO role credentials using cached token

## Setup
- Place `aws_sso_role_credentials` into a folder within your `PATH`.  
- Make the script executable, e.g. `chmod +x aws_sso_role_credentials`.  

## Usage
- Ensure you have a current sso session. One may be created with `aws sso login --profile <valid name of profile in ~/.aws/config>`
- Run `aws_sso_role_credentials <valid name of profile in ~/.aws/config>`

A current set of credentials for the specified profile (access key, secret access key, and session token) should now be present in `~/.aws/credentials` with the same profile name
