This is a fabric script to deploy website in angular though ssh with npm and git

This script builds angular app locally and commits dist/public folder to a different branch in my git repo. When that task is complete it connects to my shared server with SSH and updates public_html with updated build.
