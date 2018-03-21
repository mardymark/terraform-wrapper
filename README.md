# terraform-wrapper
Bash terraform wrapper script

## Usage
Add the script to your location in your path e.g.:
```
cp terraform /usr/local/bin/terraform
chmod +x /usr/local/bin/terraform
```

### set terraform version to use
Set terraform version using an env var:
```
export TERRAFORM_VERSION=0.11.1
```

Set terraform version for the current directory:
```
echo "0.11.1" > .terraform_version
```

### install terraform version
```
terraform install 0.11.3
```

### list installed terraform versions
```
terraform versions
```
