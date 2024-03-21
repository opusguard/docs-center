# Content Retention Manager for Confluence

## Introduction

Retention Manager for Confluence is a retention service for organizations who use Confluence. Retention Manager makes it easy for teams to track all content across Confluence against the organization’s defined data retention policies. Our app helps teams across Legal, Human Resources, and IT easily manage how long content is stored or retained across Confluence instances. This app is incredibly powerful; with the ability to index all data and purge (irreversibly remove) content in bulk actions.

### How it works

Retention Manager focuses on information governance for Confluence falling into two basic categories retention and removal.

**:file_folder: Retain content on Confluence for as long as you need it.**
: You can retain content for a set or indefinite time. Content remains available to admins even when a user archives or deletes the page or blog.

**:material-trash-can-outline: Remove content on Confluence when you no longer need it.**
: You can purge content from Confluence when it is no longer needed. Once purged, content cannot be recovered by admins or users.

### Data Management within Content Manager

Content Manager for Confluence sits directly on your Confluence instance and does not retain any data, content, or user information on external systems. The service is wholly contained within your cloud instance. When content is purged by Content Manager, it cannot be recovered by users or admins.

### Recommended First Steps

Before getting started, we recommend you read through our content on [data retention best practices](../kb/data-retention-policies-and-management-best-practices.md) and familiarize yourself with any [laws or regulations](../kb/data-retention-laws-and-regulations.md) your team may need to comply with.

> :information_source: We recommend you review all policies, practices, and processes related to this app with your company’s legal representative before you begin enforcing any retention policies. This will help you remain compliant with any applicable laws or regulations.

The following are recommended as steps to take before deploying Retention Manager for Confluence:

1. Understand why it is important to develop and implement data retention policies for your team
2. Familiarize yourself with laws and regulations you may be already subject to
3. Consider best practices when implementing content retention policies.
4. Have [a defined company retention policy](../kb/how-to-build-a-data-retention-practice.md) ahead of time.
5. Have an instance of Confluence, Free, Standard, or Premium can work with our Retention Manager apps, however a paid version of Confluence may be required for our paid Retention Manager for Confluence which contains features your team may consider critical.

> :bulb: We recommend testing the Retention Manager for Confluence app on a test or development instance of your confluence space to get familiar with it’s functionality and that any automations you enable perform as expected before deploying to your team’s primary space.

## Accessing Content Manager for Confluence

Due to the sensitivity and capability of Content Manager for Confluence, only `Site Admins` of a Confluence space can use the tool. Organizations can adjust user settings to allow for team members who need to engage with Content Manager in the Confluence Administration settings.

Content Manager for Confluence is contained in the `Forge Apps` section of `Confluence Administration tools` :gear: at the top right of a Confluence space. Access to the Admin tools are only available to Confluence Site Administrator user levels.

1. Go to Confluence Administration tools :gear:

2. On the left navigation pane, scroll down to `Forge Apps`

3. Content Manager for Confluence will be visible there.

## Key Functions of Retention Manager

| Function      | Use                                                                                                                                                                                                                                                                               |
| ------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Content Audit | This main view allows a `Site Admin` to view all content, by space, and its current status against a defined Data Retention Policy. Within content audit is where an admin can take action to delete content, purge content, and extend the retention period of specific content. |
| Extensions    | Extensions are the ability to allow any content to live on for a defined or indefinite amount of time beyond the company’s defined global retention period.                                                                                                                       |
| Audit Log     | The audit log helps you keep track of who and when policies are updated. The log also records when content status changes to deleted and purged by user or automation. The audit log is how you monitor and keep a record of your retention policy in action.                     |
| Automation    | Automation allows for you to keep your retention policy active with system processed retention enforcement and purging.                                                                                                                                                           |

## Licensing

Content Manager for Confluence has both free and paid versions. Our free or
`Lite` version captures the core values and functions of information governance
and retention policy management but with limited expanded capabilities as
outlined below.

| Features                                    | Content Manager for Confluence - Lite | Content Manager for Confluence - Full |
| ------------------------------------------- | ------------------------------------- | ------------------------------------- |
| Content Audit                               | :white_check_mark:                    | :white_check_mark:                    |
| Define Retention Policies                   | :white_check_mark:                    | :white_check_mark:                    |
| Admin Bulk Purge                            | :white_check_mark:                    | :white_check_mark:                    |
| Audit Log                                   | :white_check_mark:                    | :white_check_mark:                    |
| Retention Policy Exceptions                 | :warning: Up to 100 exceptions        | :white_check_mark:                    |
| Automated Content Deletion                  | :cross_mark:                          | :white_check_mark:                    |
| Automated Content Purge                     | :cross_mark:                          | :white_check_mark:                    |
| Indefinite Retention Content Support        | :cross_mark:                          | :white_check_mark:                    |
| Technical & Implementation Customer Support | :cross_mark:                          | :white_check_mark:                    |

## Glossary

Here are the key terms used by Content Retention Manager for Confluence (CRMC):

audit log
: A log of all the actions which users and the app automations (if enabled) have taken.

automation
: A feature that automatically deletes or purges contents according to the retention policies.

delete
: When users moves the content to the trash. The contents in trash can be restored by a Space admin. This is the same action as Confluence users deleting a content.

indefinite
: For retention policies, a content has an indefinite retention period is marked as “evergreen” for content audit, and will not be subject to automations. Note that a content with an indefinite retention period may still be deleted via Confluence by users with delete permissions and purged by space admins.

purge
: When data is removed from the trash and is permanently gone. This is the same action as Confluence space admins purging a content from the trash.

retention rule
: A policy defines a content’s retention status and the actions to be taken by CRMC to manage the content’s status or purge the content.

retention period
: The number of days that a content is certain to not be deleted by CRMC.

status
: The content’s Confluence status, which could be current, archived, or trashed.

CRMC user
: A Confluence user who has the required permissions to manage CRMC retention policies and automations, delete or purge contents, and review audit logs.
