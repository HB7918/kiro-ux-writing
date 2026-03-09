# Error Messages Guidelines

Source: AWS Content Design System

## Core Principle

Helpful error messages are concise, constructive, and diagnostic. Every error message should explain:
1. What happened
2. Why it happened (if known)
3. How the user can fix it
4. How the user can get help or find more information

## Anatomy of an Error Message

**Heading** (optional, but recommended):
Summary of error or DescriptiveErrorCode

**Message body:**
First sentence tells the user what happened and why. Second sentence says how to fix it or move toward a solution. Last part is a "Learn more" link or link to support.

## Guidelines

- Provide enough information to help users understand and fix the issue — 1-3 brief sentences
- Plainly state the issue and offer a recommended action, solution, or workaround
- Use straightforward, everyday language instead of cryptic descriptions
- Use error codes that are unique and readable, in PascalCase (e.g., ErrorCodeNotFound)
- Avoid generic messages such as "Unknown error" when possible

## Common Error Types and Examples

### Validation Errors (user input missing, incomplete, or incorrect)

Required field blank — format: `[label descriptor] [label type] is required.`

**Do:**
- "Alarm name is required."
- "Template URL is required."
- "Expiration date is required."

**Don't:**
- "Value is required."
- "This field is empty."
- "Enter all required fields."

Invalid values — format: `Enter a valid [label descriptor] [label type].`

**Do:**
- "Enter a valid email address."
- "Enter a valid subnet group name."
- "Enter a valid phone number."

**Don't:**
- "The ARN isn't valid."
- "Invalid entry."
- "The input fails to satisfy the constraints."

Input doesn't match or is already in use:

**Do:**
- "The security code doesn't match. Refresh the code and try again."
- "The instance name is already in use. Use a different name."

**Don't:**
- "The security code is wrong."
- "The input is invalid."

Character constraint violations:

**Do:**
- "The name has characters that aren't valid: #"
- "The name has too many characters. Character count: 120/50"
- "The name has too few characters. Character count: 1/50"

### Quota Errors

**Do:**
- "You've reached the quota for security groups. You can create up to five security groups. Learn more"
- "You've reached the quota of applications that you can deploy for your account. Archive or delete applications that you don't need, or request a quota increase."
- "The tag key has too many characters. Enter a tag key from 1–127 characters."

**Don't:**
- "Invalid action."
- "Quota exceeded."
- Long, apologetic messages with multiple possible workarounds

### Unsupported Action Errors

**Do:**
- "You can't delete this snapshot: {1}. You can delete snapshots only of this type: {0}. Learn more"
- "You tried to create another subnet in the same Availability Zone. Each subnet must be in a separate Availability Zone. Choose a different Availability Zone, and try again."

**Don't:**
- "Zone file contains no records to create."
- "Something went wrong!"

### Permission Errors

**Do:**
- "You don't have permission to delete the bucket {bucketname}. Learn more"

**Don't:**
- "You don't have access!"
- "Sorry, there was a problem."

For IAM permission errors on console:
- "You don't have permission to perform the following operation on the [service name] console: [operation name]. Contact your AWS administrator if you need help."

### Internal/Network Errors

**Do:**
- "DynamoDB can't process the request right now because of an issue with the server. Try again later."
- "Amazon QuickSight can't connect to this database. The host is unknown. Check that the server is running."

**Don't:**
- "Internal error."
- "System error."
- "Unexpected error. Please investigate."
- "Oops! We just blew a fuse!"

## HTTP Status Codes

- 400: Bad request
- 403: Access denied
- 404: Page not found
- 408: Request timeout
- 500+: Server errors — indicate server-side problems that must be resolved by AWS

After the standard response code and description, provide more information about the error in relation to the service functionality.

## API and CLI Error Messages

API/CLI messages tend to be more concise than console messages. Key patterns:

**Parameter values aren't valid:**
- "The name can't begin or end with a hyphen."
- "The name can contain only alphanumeric characters and hyphens."
- "The name must be unique within this AWS Region."

**Duplicate entries:**
- "The service found a duplicate name. You can't use duplicate names for load balancers or target groups."

**Parameter missing:**
- "InstanceRequirements is missing the VCpuCount parameter. Add VCpuCount, and try again."

**Unsupported operation or parameter combination:**
- "You can't specify InstanceType and InstanceRequirements in the same request. Remove either InstanceType or InstanceRequirements."
