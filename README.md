# documentation-test
##Technologies being used in distro:


##Getting started with your local environment
###setting up drupal vm;
###setting up blt and the webnydistro

##The acquia cloud site factory environment
- URL stucture - 
- how to see all sites on sitefactory: URLS to three environments
- sites factory sites on acquia insight: see how code builds are doing and artifacts
- How are each of the environments used? dev, test and prod

##Git flow and workflow dev
###General workflow (technical specifics to be found in other sections)
  - work in 2-3 wk sprints
  - Stories decided on; defects brought in
  - developer does pr against develop (perhaps sprint branch?)
  - code review: if fails story goes back to dev with info; if passes merged into develop (unless there's a reason not to)
  - qa currently done on qa.dev (if fails, create stories to fix or send original story back)
  - end of sprint: develop into master
    - review on test
    - tag depoy artifact and put on prod ( need site owner review and notification process )

- fork and prs are done agains develop
- hold over dev 

##how to do development (see also dev detail)
- set up a fork 
- se up remotes
- do a pull request (incl recommendations)

##Code review

##QA and UAT

##push to test and prod

##how to hotfix

##Dev details
- hook help
- preprocess
- twig debugging (locally turn on devel kind and devel)
- other 
