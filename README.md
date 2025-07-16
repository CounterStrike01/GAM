# User offboarding in Google Workspace

this is a Bash script wirten for Python 2.0. I designed this to automate the offboarding process for a user in a Google Workspace 
environment using GAM, a command-line tool for managing Google Workspace. Here's a quick breakdown of what the script does:

**🔍 Overview of the Script and several key offboarding tasks**

Suspends the user account.
Transfers ownership of Google Drive files to another user.
Transfers ownership of Google Calendar events.
Removes the user from all groups.
Deletes the user account (optional, depending on how the script is configured).

**✅ Pros**
Automation: Saves time by automating repetitive offboarding tasks.
Consistency: Ensures that all necessary steps are followed every time.
Customizable: You can easily modify it to suit your organization's policies.

**⚠️ Considerations**
Permissions: The GAM tool must be properly authorized with sufficient admin privileges to your domain.
Confirmation Steps: It might be risky to delete users without a confirmation prompt or backup, change as needed.
