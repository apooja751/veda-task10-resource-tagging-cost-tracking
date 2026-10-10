# Task 10: Tag and Organize Resources for Cost and Ownership Tracking

## Overview

The objective is to organize AWS resources using a consistent tagging strategy for project, environment, and ownership tracking, identify resources without tags, and generate a cost report grouped by tag.

## Objectives

- Organize AWS resources using consistent tags.
- Apply project, environment, and owner tags to selected AWS resources.
- Verify resource tags using AWS Resource Groups Tag Editor.
- Review AWS resources for missing tags.
- Create a cost and usage report using AWS Cost Explorer.
- Save and verify the report for future reference.

## Services and Tools Used

- **AWS Resource Groups Tag Editor** — Manage and verify resource tags.
- **AWS Cost Explorer** — Review cost and usage information.
- **AWS Billing and Cost Management** — Access cost management features.
- **Amazon VPC** — Network resource inventory, including subnets, route tables, and an internet gateway.
- **GitHub** — Store project documentation and screenshots.

## Resource Tagging Configuration

The following tags were configured for the selected AWS resources:

|    Tag Key  |       Tag Value       |
|-------------|-----------------------|
| Project     | Veda-Cloud-Internship |
| Environment | Learning              |
| Owner       | Pooja-Thakare         |

The tags were applied to five selected resources in the Asia Pacific (Mumbai) Region (`ap-south-1`):

- Internet Gateway
- Route Table
- Three Subnets

## Implementation Steps

1. Reviewed the existing AWS resources.
2. Inspected the VPC resource inventory.
3. Selected the internet gateway, route table, and three subnets.
4. Opened AWS Resource Groups Tag Editor.
5. Configured the project, environment, and owner tags.
6. Reviewed and applied the tag changes.
7. Verified that the selected resources contained the configured tags.
8. Audited the resource search results to identify resources without tags.
9. Opened AWS Cost Explorer and configured a monthly cost and usage report.
10. Saved the report as `Task10_Cost_Report_By_Service`, grouped by AWS service.
11. Opened Cost Explorer Saved Reports and verified that the report was present.

## Cost and Usage Report

**Report Name:** `Task10_Cost_Report_By_Service`

**Report Type:** Cost and usage

**Grouping:** Service

**Granularity:** Monthly

**Configured Date Range:** April 1, 2026 – September 30, 2026

The report was saved successfully and its presence was verified in Cost Explorer Saved Reports.

**Cost observation:** The displayed total cost was $0.00. This documents the observed result for the selected report configuration and does not establish that the AWS account had no charges outside the displayed data or date range.

## Screenshots

The following screenshots provide evidence of the implementation.

|             Screenshot         |               Description            |
|--------------------------------|--------------------------------------|
| `1_Existing_AWS_Resources`     | Initial AWS resource inventory       |
| `2_VPC_Inventory`              | VPC resource inventory               |
| `3_Selected_Resources`         | Selected resources for tagging       |
| `4_Project_Tag_Applied`        | Project tag application confirmation |
| `5_Tag_Configuration`          | Tag configuration                    |
| `6_Tags_Applied`               | Successful tag application           |
| `7_Tag_Verification`           | Verification of configured tags      |
| `8_Untagged_Resources_Audit`   | Audit of resources without tags      |
| `10_Cost_Report_Saved`         | Saved Cost Explorer report           |
| `11_Saved_Report_Verification` | Verification in Saved Reports        |

Place the screenshots in a folder named `screenshots` in the repository. If you have a screenshot numbered 9 from the Cost Explorer configuration, include it as well.

## Results

- Applied project, environment, and owner tags to five selected AWS resources.
- Confirmed successful application of the tag changes.
- Reviewed the wider resource inventory for missing tags.
- Created and saved a Cost Explorer report grouped by service.
- Verified the saved report in AWS Cost Explorer Saved Reports.

## Conclusion

This task provided practical experience with AWS resource tagging, resource inventory management, and cost reporting. Consistent tagging improves resource organization and can support cost allocation and tracking when the relevant cost allocation tags are activated and usage data becomes available.

The saved Cost Explorer report provides a reusable view of costs grouped by AWS service.

## Important Notes

- Resource tagging does not itself reduce AWS charges.
- Applying tags does not automatically activate them as cost allocation tags.
- Cost allocation tag activation and billing data availability may require additional time before tags can be used for cost analysis.
- Review AWS Billing and Cost Management regularly to monitor charges.
- Remove unused billable resources after completing practical exercises, while retaining any resources needed for other tasks.

