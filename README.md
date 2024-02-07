# aws-terraform

## Setup

1. [Sign up for AWS Account - https://portal.aws.amazon.com/billing/signup](https://portal.aws.amazon.com/billing/signup)
1. Install Terraform

   ```sh
   brew tap hashicorp/tap
   brew install hashicorp/tap/terraform
   ```

1. Install OpenTofu - https://opentofu.org/docs/intro/install/rpm/

   ```sh
   # Download the installer script:
   curl --proto '=https' --tlsv1.2 -fsSL https://get.opentofu.org/install-opentofu.sh -o install-opentofu.sh
   # Alternatively: wget --secure-protocol=TLSv1_2 --https-only https://get.opentofu.org/install-opentofu.sh -O install-opentofu.sh

   # Give it execution permissions:
   chmod +x install-opentofu.sh

   # Please inspect the downloaded script

   # Run the installer:
   ./install-opentofu.sh --install-method rpm

   # Remove the installer:
   rm install-opentofu.sh
   ```
