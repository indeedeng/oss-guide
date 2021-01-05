# Project Review (How to Open Source Indeed Code)

## Step 1: Create a JIRA ticket in OSS answering the four following questions:
1. What is the project?
1. Why do you want to open source it?
1. Does it need to be changed to remove Indeed proprietary code or setup?
1. Is it related to any existing open source project?  For instance, [Anomaly Detection](https://github.com/indeedeng/anomaly-detection) is a reimplementation of a Twitter project.  If this is the case, we should consider submitting this code back to the main project instead of hosting it as a separate repository.  

## Step 2: Review the following considerations and be ready to add them to your open source project
1. **License:** We use Apache 2.0 unless there's a reason not to (derivative work of other code with another license is a possible reason).
1. **Build system:** If it's Java, we have been using Maven, since the OSS community can work well with that and we're set up for it.  
1. **Git history:** Must be checked to ensure there are no secrets or proprietary info in old commits or old commit messages.
1. **Documentation:** The project should be well documented for use and we'll also want an engineering blog post after we release it.
1. **Inclusive terminology:** Ensure that the project follows Indeed's [guidelines for the use of inclusive terminology](https://engineering.indeedblog.com/blog/2020/07/inclusion-in-code/). 

## Step 3: Review the Repository standards

After you file an "OSS" ticket as mentioned above, OSS will get back to you with relevant information to start the review process. After the initial conversation with the team, you will want to have a plan to implement the repository standards that we've outlined for open source projects. These should be implemented before the project goes live and is open sourced.

## Final Considerations: 
We encourage open sourcing, but we want to make sure the code is not critical special sauce.  Signoff from the Open Source Programs Office will need to be captured in the OSS JIRA ticket before final release.  
