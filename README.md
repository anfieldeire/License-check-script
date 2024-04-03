# Servicenow Scheduled Job Scripts
- These script check for user activity in the demand module and related modules and remove licenses from users if there is not enough activity
- Notification script checks last 3 months usage activity for users who have a demand license and notifies them
- Group removal script runs 1 week later and rechecks license and usage activity again.
    - Removes users from specified groups if there is no activity in 3 months  
