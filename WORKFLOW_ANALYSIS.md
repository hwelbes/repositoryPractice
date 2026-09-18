What triggers this workflow to run?
  Any Push or Pull Request to the main branch.

What are the four main steps this workflow performs?
  Step 1: Get the code from the repository
  Step 2: Validate HTML files
  Step 3: Check for broken links
  Step 4: Upload the built site for deployment

What does the "Checkout code" step do and why is it necessary?
  Labels the Step so it is easy to read in the workflow logs.
  It is necessary in case something happens during the workflow so that you can easy find where the issue is sprouting from.

What is the purpose of the environment configuration?
  To give a location where you can track the history of your deployments and to provide a direct link to the live site.

How does this automated deployment improve reliability compared to manual deployment?
  Makes everything consistent and faster. You know what is being triggered each time you do it.

What would happen if you pushed code to a different branch?
  The workflow wouldn't be triggered
