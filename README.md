# Canary — Privacy Policy

**Last updated:** November 17, 2026

## 1. About Canary
Canary is an Atlassian Forge application developed by Carlos Ferreiro to test Jira Automation behavior through controlled test issues.
Canary operates within Atlassian Cloud and is intended for use in dedicated test projects.

## 2. Information We Process
To perform its functions, Canary accesses and processes:
- Jira project names and identifiers.
- Test issue identifiers, labels and creation timestamps.
- Issue change histories, including relevant modification information.
- User permissions and authentication context required to authorize operations.
- Test configurations and execution results.

Canary does not require users to provide passwords or payment information.

## 3. Data Storage and Retention
Canary stores up to 50 recent test execution records using Atlassian Forge Key-Value Store (KVS).
Records may contain project identifiers, issue keys, configured labels, timestamps and execution metadata.
Authorized users can view records associated with projects they can access. Users with project administration permissions can clear the corresponding execution history.
Stored records may remain until deleted or replaced by newer executions.
Clearing Canary's history does not delete Jira issues created during testing.

## 4. Third-Party Services and Notifications
Canary operates using Atlassian Forge and Jira Cloud.
The application does not intentionally transmit execution records to independent analytics or advertising services.
However, creating test issues may activate Jira Automation rules, notifications, webhooks or other integrations configured by the customer's organization.
Canary cannot prevent these external effects. Users should run tests in dedicated projects.

## 5. Data Security
Canary uses Atlassian Forge permissions and Jira authorization controls to restrict access and operations.
The application does not maintain a separate external database or authentication system.
Data processing and storage are subject to the applicable Atlassian Cloud infrastructure and security controls.

## 6. Your Choices and Rights
Users should contact their Jira organization administrator to manage permissions and Jira issues.
For questions about Canary's stored execution records, access requests or deletion requests, contact the developer using the address below.
Applicable data protection rights depend on your jurisdiction.

## 7. Contact
- **Developer:** Carlos Ferreiro
- **Application:** Canary
- **Email:** josecarlosvelosoferreiro@gmail.com

For information about Atlassian's processing of data, consult the [Atlassian Privacy Policy](https://www.atlassian.com/legal/privacy-policy).
