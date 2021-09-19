# terra-form-test-techhub
Terratest is a Go library developed at Gruntwork, that makes it easier to write automated tests for our infrastructure code. It provides a variety of helper functions and patterns for common infrastructure testing tasks but here we will be discussing about Testing Terraform code.

# To Run this application
git clone https://github.com/imnitin28/terra-form-test-techhub.git  <br />
cd test  <br />
go mod init "<MODULE_NAME>"  <br />
**MODULE_NAME would be github.com/<YOUR_USERNAME>/<YOUR_REPO_NAME>**  <br />
go mod init github.com/imnitin28/terra-form-test-techhub  <br />
go run

--------------------------------------------------------------------------------------------------------------------------------------------------------------------

go mod init "<MODULE_NAME>" would create go.mod file into test folder.  <br />
On running **go test** for the first time you would get go.sum file created.
