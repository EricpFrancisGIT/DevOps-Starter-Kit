# Eric Paul Michael Francis

Columbia, Missouri  
Email: eric.francis1103@gmail.com  
Phone: 573-268-0802  
LinkedIn: https://www.linkedin.com/in/eric-francis-ms  
GitHub: [GitHub Username]  

---

## SUMMARY

Entry-level DevOps Engineer transitioning from VMWare Administration with a passion for automation, cloud technologies, and system reliability. Skilled in scripting, cloud fundamentals, and deploying infrastructure using modern DevOps tools. Currently building hands-on projects and pursuing AWS certifications to accelerate a career in cloud engineering. Strong communicator and self-learner with a desire to contribute to high-performing technical teams.

---

## SKILLS

- **Languages:** Bash, PowerShell, Python (boto3 primarily)  
- **DevOps & Cloud:** AWS (EC2, S3, IAM, Lambda, CloudFormation, CloudWatch), GitHub Actions, Terraform (IaC), Docker (basic), AWS CLI, EventBridge  
- **CI/CD & Automation:** GitHub Actions, Git, GitHub, CodePipeline (familiar), YAML  
- **Monitoring & Logging:** AWS CloudWatch, EC2 Logs  

---

## PROJECTS

### Prompt Deployment Pipeline | Amazon Bedrock + S3 + GitHub Actions  
*Use Case: Automate AI-powered content creation and publishing for static sites.*

- Created a GitHub-based CI/CD workflow to process prompt templates and config files  
- Built a Python script (`process_prompt.py`) that:  
  - Loads and renders prompt templates using variables from config files  
  - Sends structured prompts to Amazon Bedrock for content generation  
  - Saves outputs as `.html` or `.md` files and uploads to S3 for static website hosting  
- Used environment-specific prefixes (`beta/`, `prod/`) to separate test and live content  
- Managed workflow triggers using PRs and merges, with secrets securely handled in GitHub Actions  

### Multilingual Audio Pipeline | Amazon Transcribe + Translate + Polly + S3 + GitHub Actions  
*Use Case: Automate voice-to-voice translation for .mp3 content.*

- Developed a Python script (`process_audio.py`) to:  
  - Upload input .mp3 files to S3  
  - Transcribe English audio using Amazon Transcribe  
  - Translate text into other languages with Amazon Translate  
  - Generate multilingual speech using Amazon Polly  
  - Save outputs to structured S3 paths for `transcripts/`, `translations/`, and `audio_outputs/`  
- Automated processing via GitHub Actions workflows for both PR (beta) and main (prod) branches  
- Used GitHub Secrets to securely manage AWS credentials and environment variables  

### Two-Tier Web Architecture on AWS | EC2 + RDS + VPC  
*Use Case: Deploy a secure and scalable content management website.*

- Launched a custom VPC with public and private subnets, configured routing tables and Internet Gateway  
- Deployed CMS on an Ubuntu EC2 instance (web tier), with MySQL database hosted on Amazon RDS (database tier)  
- Hardened networking using security groups and subnet isolation (EC2 in public, RDS in private)  
- Verified application connectivity and documented the benefits of two-tier architecture  

### EC2 Shutdown Automation | AWS Lambda + GitHub Actions + CloudFormation  
*Use Case: Reduce unnecessary EC2 runtime costs for non-production environments.*

- Built a Python Lambda function using `boto3` to identify and stop EC2 instances based on state and tags  
- Scheduled shutdowns via Amazon EventBridge  
- Created an S3-hosted deployment package and used CloudFormation templates to deploy the Lambda with IAM roles  
- Automated deployment using separate GitHub Actions workflows for beta and prod environments  
- Managed environment-specific parameters and AWS credentials using GitHub Secrets  

---

## EXPERIENCE

### Lead, Infrastructure Specialist  
**Kyndryl** — Columbia, Missouri  
*August 2021 - Present*

- coordination of patching Windows AWS EC2 instances within different environments (Shared/Dev/Prod) for City of Chicago, collecting patching evidence and remediating any open advisories, advising application owners and city personnel as to status 
- creating and allocating storage datastores in vSphere environment along with updating ESXI hosts and associated VMWare packages on a quarterly basis while handling requests for City of Chicago assets. 
- documenting processes and procedures for team personnel regarding different AWS services in use within City Of Chicago, making recommendations for additional services should they be needed to Chief System Architect.  

---

## EDUCATION

**High School Diploma**  
Hopkins High School, Minnetonka, Minnesota — 1997

**Bachelor of Science, Information Technology**  
Colorado Technical University, Colorado Springs, Colorado — 2011

**Master of Science, Cloud Computing Architecture**  
University of Maryland, Adelphi, Maryland — 2020

---

## CERTIFICATIONS

- AWS Certified Cloud Practitioner
- AWS Certified Solutions Architect - Associate
- AWS SysOps Administrator - *In Progress*
- AWS Certified Developer – Associate – *In Progress*  
- Certified AI Practitioner (CAIP) – *Planned*  
- HashiCorp Certified: Terraform Associate – *Planned*  
