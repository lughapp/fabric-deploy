This is a fabric script to deploy my website in angular though ssh with npm and git

It builds angular app locally and commits dist/public folder to a different branch in my git repo.
When that task is complete it connects to my shared server with SSH, pulls changes on a temp folder and updates public_html with updated build.
