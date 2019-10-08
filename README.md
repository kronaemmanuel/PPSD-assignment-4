# PPSD Assignment 4

## Assignment Task
-   What is Software Deployment?
    -   Manual Deployment
    -   Automated Deployment
        -   Deployment Tools
    -   Best practices for Deployment
-   Server Backups
    -   Best Practices for Backups

### What is Software Deployment?

Software deployment is a post-production process that is performed between the acquisition and the execution of the software.

It includes a number of inter-related activites such as:

- Release of software at the end of the development cycle
- Configuration of the software
- Installation of the software into the execution environment
- Activation of the software

It may also include post installation activities

- Monitoring
- Deactivation
- Updating
- Reconfiguration
- Adaptation
- Redeploying
- Undeploying

### Manual Deployment (aka the SysAdmin approach)

- Typically starts with a sysadmin who is tasked with assembling the existing software components and deploying them to work together to produce a *service*
- Sysadmin runs the service and responds to the events and updates as they occur
- Only intended for advanced users when more control of applicationn server is required 

**Advantages**
- A familiar industry paradigm for companies in terms of hiring and running staff
- An array of existing tools, software components and integration systems are already available

**Disadvantage**
- As the system grows in complexity and traffic volume, the sysadmin team needs to grow too
- Indirect costs such as disagreement in philosphies between teams within the same company

### Automatic Deployment

- Software engineers setup automated processes which can take the latest code, run tests on it and deploy it

**Advantages**
- Can easilly implement progressive rollouts
- Problems can be detected accurately and quickly without input from the users
- Changes can be rolled back safely when problems arise

**Disadvantages**
- Practically none

### Best Practices

Best practices for Automated deployment systems in modern businesses are as follows:

1. **Monitoring:** Always have a thoughtfully designed monitoring infrastructure. Without it, there will be no way to tell if a service is working or not
2. **Incident Response:** While it is important to answer tickets, it is even better to instead give your time towards creating solutions that will not only fix the problem for the long term.
3. **Postmortem and Root-Cause Analysis:** Understand what went wrong. Cultivate a blameless postmortem culture.
4. **Testing:** Create tests that will assure that the problems don't go under the radar the next time.
5. **Capacity Planning:** Make systems that can estimate traffic, system use etc. So it avoids cascading failures.
6. **Data Integrity:** Maintaining data integrity is key. Make sure that your data remains safe. Use methodologies such as distributed consesus, data processing pipelines to make sure that your data is secure.
7. **Product Launch:** Make sure that your customers are getting the optimal experience from day one. Keeping track of previous deployments and their effects is key to nailing this.

## Resources

- [DevOps Introduction FreeCodeCamp](https://www.youtube.com/watch?v=UqMUoINlKnY)
- [Software Development Paper by Dearle](http://www.cs.tufts.edu/comp/250SA/papers/dearle2007.pdf)
- [Site Reliability Engineering](https://landing.google.com/sre/sre-book)
- [12 Factors of Modern Software development](https://12factor.net/)
