WhiteSource-Scan Orb
==============================

### General Information
CircleCi is continuous integration development practice that is used by software teams allowing them to build, test and deploy applications on multiple platforms in an easier and quicker fashion.


### What is an Orb?

Orbs are CircleCI configuration packages that can be shared across projects. Orbs allow you to make a single bundle of jobs, commands, and executors.

### What is WhiteSource Scanner Orb?

The WhiteSource Scanner Orb is a simple tool that extracts descriptive information from the open source libraries located on your file system and integrates them with WhiteSource.

WhiteSource Scanner Orb enables you to check your container images for compliance and security. Make sure to add the orb to your config.yml file in order to start using it.

The scanner itself is a small, easy to implement vulnerability scanning tool.

### Related Parameters:
api_key (Required) -  Unique identifier of the organization. Can be retrieved from the admin page in your WhiteSource account.

directory - Comma separated list of directories and / or files to scan.

config_file_path - Configuration file name (including file path). Defaults to ./whitesource-fs-agent.config 

| Parameter  | Description | Required | Default | Type |
| -----------| -------------------------------------------------------------------------------------------------------- | ------------- | ------------- | ------------- |
| api_key  |  Unique identifier of the organization. Can be retrieved from the admin page in your WhiteSource account. | Yes | - | String |
