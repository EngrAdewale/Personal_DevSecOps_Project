# í»¡ï¸ DevSecOps (Development + Security + Operations)

It's a way of building software where **developers**, **security people**, and **IT teams** work together from the start â to make apps **faster and safer**.

---

## í´ Key Features

### âï¸ CI/CD (Continuous Integration / Continuous Delivery)

This is how developers:

- Write code â **(Repo)**
- Test and build it automatically â **(CI)**
- Deliver or deploy it safely to users â **(CD)**

> Imagine writing a letter, checking it, and mailing it â all done by a robot every time you make changes!


---

## í·± Infrastructure as Code (IaC)

Instead of setting up servers manually, we write **code** to do it.  
Itâs like writing a **recipe** for your computers.

- **Terraform**: Builds the machines (like servers, networks)
- **Ansible**: Sets them up (like installing programs, passwords)

---

## í³¦ Containerization

This means putting apps in a **box (container)** so they work the same anywhere.

**Example:**

---

## í¾ï¸ Orchestration (Kubernetes)

If you have **many containers**, **Kubernetes** is like a manager that:

- Keeps them running  
- Restarts them if they crash  
- Puts them in the right place  

---

## í³ Monitoring

To keep everything healthy, we need to **watch our systems**.

1. **Node Metrics**: Like CPU, memory â check how the machines are doing  
2. **Logging**: Keep records of what apps and servers are doing (like a security camera)  
   - We use **ELK Stack** (Elasticsearch, Logstash, Kibana) to store and view logs

---

## íº Deployment Strategies (Ways to Release Updates)

- **Rolling Update**: Replace old version little by little, no downtime  
- **Blue-Green**: Keep two versions (Blue = Old, Green = New), switch when ready  
- **Rollback**: Go back to the old version if something breaks  
- **Canary Deployment**: Release to a small group first, then everyone  
- **Recreate**: Stop old version completely, then start new (may cause downtime)  
- **A/B Testing**: Show different versions to users, compare results  
- **Shadow Deployment**: Run the new version silently in the background for testing  

---

