# How the Sausage is Really Made

CloudOps for Red Teamers

Note: This presenter simply showed terraform operations for building assets in a cloud. Not a lot of information relevant to red teamers in my opinion. 

John Ventura

- Development is one of the best ways to learn security. 
- Config as code: 
	- Canonical record of cloud resources
	- Enforce best practices
	- Redeployment is actually possible
- Code solutions: 
	- AWS CloudFormation
	- GCP Deployment Mgr
	- Azure Resource MGR
	- Multi-Cloud
		- Terraform
		- Ansible
		- Chef
- Don't put sensitive data in metadata or tags
- Make sure buckets are private
- Turn on LOGGING and telemetry
