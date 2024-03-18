## Learning Activities & Resources
This week I needed to learn how to deploy a WordPress site to AWS for my second assignment  
- [Setup WordPress on an EC2 Instance Running Docker - Medium Article](https://ajimbong.medium.com/setup-wordpress-on-an-ec2-instance-running-docker-30dabc4ee696) *Read all + Followed instructions*
- [Docker Docs](https://docs.docker.com) *Read where necessary*
- [awswordpresss by lindsaymarkward GitHub Repo](https://github.com/lindsaymarkward/awswordpress) *Read all + Followed instructions*
- [vagrant-aws by mitchellh GitHub Repo](https://github.com/mitchellh/vagrant-aws) *Read all*
## Estimated Hours
- 1 hour reading
- *There really wasn't much time that I needed to devote to learning for this week as the content that I was dealing with was mostly things I had already learned in previous weeks*
## Content Insights
- vagrant-aws seemed like a great option to use, however the vagrant plugin would not successfully install, most likely since the repo has been archived it is simply too outdated to work
- Using Docker compose on a AWS EC2 virtual machine allows for a very easy way to create all the necessary parts of a WordPress install with one docker-compose file 
- YAML (yet another markup language) files (what docker files use) must be indented correctly, using 2 spaces for nesting. 
	- This led to an issue where when I copied text into my docker-compose file, it wasn't indented correctly, resulting in an error
## Career/Employability/Learning Insights
- Getting used to how industry standard services like AWS work, will help ready me for jobs that may require these skills in the future
