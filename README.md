# Policy templates

Workflow templates shared across projects.

## Usage

`policyscan.yml` and `policyscan-java.yml` - These templates perform an Upload and Scan (Policy Scan) are differentiated only by how they package the code for the policy scan. Each has required inputs that must be set in the repo's secrets to run successfully:

- VERACODE_APP_NAME - name to be used for application profile
- VERACODE_API_ID - API ID to be used when performing upload and scan
- VERACODE_API_KEY - API Key to be used when performing upload and scan
