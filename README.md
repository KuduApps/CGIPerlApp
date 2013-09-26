CGIPerlApp
==========

This demontrates how to enable website using cgi written in perl script.

  1. Clone this repository.
  2. Run `build.cmd`.  This will create `artifacts\Release\zip` folder and couple of files.
  3. Copy `Deployment Trigger Url` from Azure portal for your website (CONFIGURE TAB).
  4. Run `artifacts\Release\zip\DeployExtension.cmd "<url>"`.
  5. Add an AppSetting `WEBSITE_PRIVATE_EXTENSIONS=1` to your site.
  6. Browse the your site `<url>/default.pl`

That's it.
  
