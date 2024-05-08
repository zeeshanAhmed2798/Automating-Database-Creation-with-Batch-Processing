@echo off
@echo Executing my T-SQL Table creation Script
SQLCMD -s . -d social_media -E -i "D:\4th semester\Database lab\Project"

IF ERRORLEVEL 1 (
    ECHO Error: Script execution failed.
) ELSE (
    ECHO Script executed successfully.
)

PAUSE
