# Roadmaps
Roadmaps of various technology disciplines (DevOps, Business Intelligence) i've made for people learning

# DevOps
## My DevOps Definition
DevOps is a culture and practice that aims at unifying software development and operations. (Thanks Wikipedia!) It's a pretty good description and this is what I live by. Tot ake it a step further by unifying all of the various groups you hopefully get more input at the beginning stages which makes for hopefully smoother and more resilient deployments. For the purposes of this document I will be going down the path of what the industry looks at DevOps as and that's release management and site reliability

## Stuff you should know or get familiar with
### Your company's deveopment and deployment pipeline
* What is it?
* Is it as efficient as it can be?
* How long does a deployment take?
* Can you recover quickly after a failure?
* Are your systems / nodes pets or cattle?
* How much massaging do you have to do to the systems per deployment?
* How much is automated?

Some good resources for learning about pipelines and best practices:
* Architecting for Continuous Delivery Blog post from snap-ci: https://github.com/snap-ci/snap-ci-blog-content/blob/master/posts/2015-11-24-architecting-for-continuous-delivery.md
* Continuous Delivery: Reliable Software Releases through Build, Test, and Deployment Automation: https://www.amazon.com/Continuous-Delivery-Deployment-Automation-Addison-Wesley/dp/0321601912/ref=sr_1_1?ie=UTF8&qid=1514309814&sr=8-1&keywords=CI%2FCD
* CI/CD 4 Part series from Bundyfx: https://youtu.be/XO0ziCtmeW8

### Whats Coming and worth your time
* Scripting
    * Python - Why Python? It's awesome, readily available and it's used in Ansible (awesome system management).
        * Learn Python The Hardway: https://learnpythonthehardway.org/
    * Powershell - WHy Powershell? It's just about everywhere and makes Windows administration so much easier!
        * From the Scripting Guys, old but useful: https://blogs.technet.microsoft.com/heyscriptingguy/2015/01/04/weekend-scripter-the-best-ways-to-learn-powershell/
        * Learn Windows PowerShell in a Month of Lunches: https://www.amazon.com/Learn-Windows-PowerShell-Month-Lunches/dp/1617291080
    * Go - Why Go? Super fast! Powers a lot of the newer tools out there specifically Docker
        * Why Go: https://medium.com/@kevalpatel2106/why-should-you-learn-go-f607681fad65
        * Learn Go, excellent list on github: https://github.com/golang/go/wiki/Learn
* Managing Systems and Applications
    * Ansible - Easy to use (simple yaml), and has Linux plus Windows support. Only needs SSH or winrm
        * DigitalOcean Brian Hogan: https://www.digitalocean.com/community/tutorials/how-to-install-and-configure-ansible-on-centos-7
        * Cloud Academy: https://youtu.be/iVWmbStE1MM
        * edureka!: https://www.youtube.com/watch?v=dCQpaTTTv98
    * Cloud Systems
        * Amazon Web Services AWS: 
        * Google Cloud Services GCS:
        * Azure:
    * Kubernetes - Containerization orchestration and clustering, super powerful and in my eyes has done a lot more then Docker Swarm
        * Kelsey Hightower (My Hero) Kubernetes The Hard Way: https://github.com/kelseyhightower/kubernetes-the-hard-way
        * Kubernetes Tutorials: https://kubernetes.io/docs/tutorials/
        * What is kubernetes: https://www.redhat.com/en/topics/containers/what-is-kubernetes
    * Docker
    * Consul
    * Terraform
    * Packer
* Development Tools:
    * Nomad
    * Jenkins
* Metrics / Reporting / Logging
    * FluentD
    * OpenTracing
    * Prometheus
    * Grafana
    * Elasticsearch Logstash Kibana - ELK
    * Commercial Splunk

### Concepts
* Continuous Delivery
* Continuous Integration
* Culture
* Deveopment best practices
* Operations best practices
* System Architecture best practices