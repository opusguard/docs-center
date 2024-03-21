# Glossary

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
