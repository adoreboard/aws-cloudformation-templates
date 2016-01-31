AWS CloudFormation Templates


# Introduction

This repo contains various AWS cloudformation templates for creating the following database / messaging system clusters: -

1. MongoDB Production Cluster
2. Elasticsearch Cluster
3. RabbitMQ Cluster

**NOTE:** These templates assume that the following is in place: -

1. Security Groups created for each cluster.
2. VPC created - these will all be installed in the private subnet.
3. Route53 private zone created (recommended best practices).
4. AWS IAM role created called MonitorRole - this is for installing CloudWatch metrics such as memory / diskspace monitoring.

Hopefully you find these templates useful - feel free to edit, remove and add sections depending on your use-case.

# Download

To download run the following command: -

    git clone https://github.com/adoreboard/aws-cloudformation-templates.git

