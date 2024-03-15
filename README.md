# GitHub Action: Encoding Conversion

This GitHub Action provides a sample workflow to convert file encodings. To use this action, follow the instructions below:

## Usage

1. Copy the YAML file (`encoding-conversion.yml`) to your GitHub Actions workflow directory. 
2. Specify the required variables in the YAML file.

## Required Variables

- `folder_from`: Specify the source folder name from which files will be converted.
- `encode_from`: Specify the source encoding for conversion.
- `folder_to`: Specify the target folder name where converted files will be stored.
- `encode_to`: Specify the target encoding for conversion.
- `commit_message`: Modify this variable to set a custom commit message for Git.
- `user_email`: Specify the email address for Git commits.
- `user_name`: Specify the Git username for commits.

## References
https://docs.github.com/en/actions
