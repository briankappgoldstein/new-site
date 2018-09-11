---
title: WP Campus Notes 2018
categories: WordPress WPCampus events notes webDevelopment higherEd Spry
---

I was fortunate enough to get to be able to attend a day of WP Campus' presentations this year, since it was hosted in my home city. 

Now, all the sessions are available to watch here: [https://2018.wpcampus.org/watch/](https://2018.wpcampus.org/watch/)

Here are the notes straight from my notepad: 

### Nobody Puts WP in a Corner

Develop on Desktop
Prove on Local
Publish to container

git branch 
git checkout
git pull origin master
git merge 
git push origin master (with or without tag)

https://deliciousbrains.com/composer-premium-wordpress-plugins/

Docker
- Wrapper around Linux Containers
- often compared to a VM
- Build once run anywhere
- Developer worries about whats inside
- Ops worries about whats outside

Dockerfile for Docker image
From/Label

*need to grab the example docker file/slides*

Image is auto built with continuous integration file, tagged and added to registry

*Gitlab*

*similar to but streamlined compared to Sense deploy*

Is this worth doing? Advantages: versioning/Rollback for your entire server. Future proof for Collaboration. And cross team collaboration. Transparency. 

How’d you sell it?
- small team easier sell

Lessons learned 
- wrapping your head around Docker
- Lack of a command line
- Swarm issues 
- Clean out registry builds
- Remember Deploy Keys

Future improvements
More CI Auto
Fancy import to dev
WPCLI
Replicas/Prefetch
Kubernetes? https://kubernetes.io/ to manage containers


resources: 
-Servers for Hackers
-Getting started with CI for WP


Security Concerns? 
- Build your own repos
- secret variables/private keys?
- build process verification

How are you managing docker file? Once its in the registry you have a release (?)


### Five Years of WordPress at a Public University - Jeremy Felt

leaving WSU to start his own agency
WP Core team contributor for 6 years
VVV creator
Blogs about Fish Taco
loves Free and Open Source Software (FOSS)
Kenyon Butterfield’s threefold purpose of university - organ of research, educator of students, distributor of information.

- reality: not everyone is ready to share
- reality: the university is an enterprise
- Assumption: develop and iterate with speed
- Success: Build a community
- Failure: Shipping features was tough
- Failure: Open Registration
- Success: Never been hacked
- Success: WP core contributions
- Approach: Pick a plugin policy
    - Not every plugin is an enterprise plugin
    - *gravity forms*
- Approach: Beware the boilerplate
- Approach: Identify the problem before solving it
- Approach: Contribute to WordPress Community
- Plugin I like Query Monitor
- Plugin I like User Switching
- Plugin I like Restricted Site Access 
- Plugin I like WP Document Revisions
- Human made cron jobs
- human made S3 uploads 
- Customize Snapshot
- 

### Lessons from Carleton
“Sometimes real life isn’t cutting edge”
CDN -> Reverse Proxy —> Prod Servers —> Prod MYSQL —> Staging —> Dev —> Local
DeployHQ - External Service that looks at github repo, it SSHs in and updates the files that changed

### Future Proof Panel:
- be kind to your future self
- design so you don’t have to redesign
- web design is not a project because projects have an end date
- educate stakeholders
- The “re” part of “redesign” is the important part - either you didn’t do it correctly the first time or things have changed enough that you have to do it again. 
- can’t not prioritize Accessibility, Security, Privacy
- blocks, not whole pages (Gutenberg)
- if you’re not doing smart things today, an “Ooh shiny” won’t fix you tomorrow
- Tools before Strategy leads to Tragedy

I also made a 10 in 10 powerpoint presentation for Spry Digital, internally. I have a copy and might share it by request.