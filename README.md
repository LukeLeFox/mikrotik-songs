# mikrotik-songs 
SECURITY COPY FROM ALEXANDERFEFELOV

# Installation
Add content of .rsc files as scripts under /system script.

# Usage

/system script run RINGTONE_NAME


# Schedule
/system scheduler add name="RINGTONE_NAME" on-event="/system script run RINGTONE_NAME" interval=10
