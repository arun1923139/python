# Python — DevOps Scripting & Automation

A collection of Python scripts and Jupyter notebooks covering Python fundamentals, system automation, cloud interaction with AWS Boto3, and DevOps-focused scripting tasks.

---

## Topics Covered

### Core Python
- Variables, data types and data structures (lists, dicts, tuples, sets)
- String formatting and slicing
- Operators, conditions and loops
- Functions (parameters, return values, scope)
- Built-in methods and modules
- Exception handling

### System & OS Automation
- File and directory operations with the `os` module
- Process management and shell command execution
- Log parsing and text file manipulation
- Automated report generation

### Cloud Automation with Boto3 (AWS SDK)
- EC2 instance management (start, stop, describe)
- S3 bucket operations (upload, download, list objects)
- IAM user and policy interactions
- Automating AWS tasks with Python scripts

### DevOps Scripting
- JSON and YAML parsing for config file handling
- Python Fabric for remote server automation over SSH
- Writing reusable automation scripts for infrastructure tasks

---

## Repository Structure

```
python/
├── basics/
│   ├── variables.ipynb
│   ├── data_structures.ipynb
│   ├── functions.ipynb
│   └── exception_handling.ipynb
├── os_tasks/
│   ├── file_operations.ipynb
│   └── process_management.ipynb
├── boto3/
│   ├── ec2_management.ipynb
│   ├── s3_operations.ipynb
│   └── iam_tasks.ipynb
└── automation/
    ├── fabric_demo.ipynb
    └── yaml_json_parsing.ipynb
```

---

## Key Libraries Used

| Library | Purpose |
|---------|---------|
| `boto3` | AWS SDK — cloud resource automation |
| `fabric` | Remote server automation over SSH |
| `os` / `sys` | OS-level operations and process management |
| `json` / `yaml` | Config file parsing |
| `subprocess` | Shell command execution from Python |

---

## Key Skills Demonstrated

- Python scripting for DevOps and infrastructure automation
- AWS cloud resource management using Boto3
- Remote server automation with Fabric
- YAML/JSON config parsing (essential for K8s and Ansible work)
- Writing reusable, maintainable Python scripts
