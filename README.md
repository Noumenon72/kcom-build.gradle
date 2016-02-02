# kcom-build.gradle
Automated build process for private forum kovaciny.com.

This really speeded up development compared to the old manual process.
Uses [gradle-js-plugin](https://github.com/eriwen/gradle-js-plugin) to lint and minify 
Javascript before upload.
Detects changed files and uploads them to the server via FTP (the only way I have access).
