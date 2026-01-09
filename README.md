# Resumate

## Introduction
Resumate is a web tool that helps people create resumes easily. The user fills in simple text boxes with their personal information, work experience, and skills. After that, the website creates a ready-to-use resume based on the given information.

The site offers many different resume styles, so users can choose the one they like most or the one that fits the job they are applying for. Resumate makes resume creation faster and easier, especially for people who do not have much experience with design or formatting.

## During the project
During the project, I realized that traditional programming is not the area I enjoy the most. I prefer working with cloud services, infrastructure, and architecture design. This project helped me confirm that cloud technologies are the area where I want to focus in my future career.

One of my main goals was to build a working cloud architecture for the application, and this goal was achieved. I also learned new backend programming skills while working on the project. In addition to technical skills, I improved my teamwork skills by working together with others and solving problems as a team.

## The app

### Infrastructure
Here you can see the AWS architecture diagram and some explanations on the choices.
![Architecture diagram](images/aws_architecture.png)

* S3 static host bucket - Simple and easy way to host a frontend on cloud.
* CloudFront (not in the picture) - CloudFront is added to deliver the website and resume files faster. It also allowed us to make paths for some functions that were not working without them.
* Elastic Beanstalk backend - Between Lambda functions or Elastic Beanstalk it was an easy choice to use Elastic Beanstalk since it handles servers, scaling, load balancing, and deployment.

## Start of the project
This project shows my learning process and development during the course. At the beginning of the course, I was able to build cloud architectures with guidance, and I had a basic understanding of backend programming. After completing the project, my cloud skills, especially with AWS, improved significantly, and I became more confident working with cloud-based systems.

The main part of the project is presented through a cloud architecture diagram with clear explanations of the technology choices. This helps show how the application is built and why certain cloud services were selected. The side work of the project is shown through backend code snippets that I had to learn and write so that the application works correctly in the cloud environment.

## Main features
This code creates a preview of the resume on the website.
The resume is shown like an A4 paper inside the browser and it's scaled automatically to fit the screen, so it looks good on all screen sizes.

![preview image](images/preview_ss.png)


This code creates a backend API endpoint that generates a CV as a PDF file.
It receives the users data from the input fields, builds it into a resume using an HTML template, converts the template into an A4 PDF with Puppeteer, uploads the PDF to Amazon S3 bucket, and finally returns a CloudFront link where the CV can be downloaded.

![createCV image](images/createcv_ss.png)

Most of the thigns shown here are something I haven't done before or even thought about how to do them and through that I now have a new set of skills to put in use in the future. Setting up the backend was quite difficult since it wouldn't start at first but I figured out while setting up Elastic Beanstalk there was an error in the configuration. After that getting the front- and backend working together in the cloud was much harder than I anticipated but with CloudFront and fixing the code I got it working.


## Overall
###Key achievements

Built a complete cloud-based CV generation system using AWS
Successfully generated and distributed PDFs using Puppeteer, S3, and CloudFront
Designed a scalable cloud architecture

I learned a lot of new things and got to use my existing AWS skills to understand what we need and how to set up the basic infrastructure. In my opinion, this project was a good choice for me to improve my skills in cloud services and overall I am happy with how everything turned out even though there were times where I was having a really hard time. 

### Future
In the future, I see myself working on different projects, but I hope to focus mainly on cloud services rather than traditional programming tasks. My career goal is to work in a role where I can design cloud architectures or work as a cloud consultant.

The course supported these goals well by teaching how to move from an idea to architecture design and implementation. It also helped me understand how to choose the right technologies based on the project needs.

### After school
To reach my goals, I still need to deepen my technical skills, gain more work experience, and complete AWS certifications. My strengths include problem-solving skills, patience, and strong interest in cloud services, especially AWS. These strengths became clearer during the project, as I faced new challenges and enjoyed solving them.

I chose these documents for my portfolio because they best show my work, my learning process, and the challenges I faced while building a cloud-based application.




# MAHDOLLINEN PÄIVITETTY VERSIO

# Resumate

## 1. Introduction
**Resumate** is a web tool that helps people create resumes easily. Users fill in simple text boxes with personal information, work experience, and skills. The website then generates a ready-to-use resume.  

- Offers multiple resume styles to suit different jobs or personal preferences.  
- Makes resume creation faster and easier, especially for users with limited design experience.  

---

## 2. My Role & Learning During the Project
During the project, I discovered that I prefer working with **cloud services, infrastructure, and architecture design** over traditional programming.  

**What I achieved:**  
- Built a working **cloud architecture** for the application.  
- Learned new **backend programming skills**.  
- Improved **teamwork skills** by collaborating with others and solving problems together.  

---

## 3. Project Overview

### 3.1 Infrastructure
**AWS Architecture:**  
![Architecture diagram](images/aws_architecture.png)

- **S3 static host bucket** – Simple hosting for the frontend.  
- **CloudFront** – Delivers the website and resume files faster; fixes path issues.  
- **Elastic Beanstalk backend** – Handles servers, scaling, load balancing, and deployment.  

> Choosing Elastic Beanstalk over Lambda functions made deployment easier and allowed me to focus on architecture rather than manual configuration.  

---

### 3.2 Project Start
At the beginning of the course:  
- Able to build cloud architectures with guidance.  
- Had a basic understanding of backend programming.  

After completing the project:  
- Improved **AWS cloud skills** significantly.  
- Became more confident in working with **cloud-based systems**.  
- Learned to integrate frontend and backend in the cloud.  

---

### 3.3 Main Features

**Resume Preview:**  
- Displays a resume like an A4 page in the browser.  
- Automatically scales to fit different screen sizes.  
![preview image](images/preview_ss.png)  

**PDF Generation (Backend API):**  
- Receives user data from input fields.  
- Builds a resume using an HTML template.  
- Converts it to A4 PDF using Puppeteer.  
- Uploads PDF to **Amazon S3** and returns a **CloudFront download link**.  
![createCV image](images/createcv_ss.png)  

**Challenges:**  
- Backend initially failed to start; resolved configuration issues in Elastic Beanstalk.  
- Integrating frontend and backend in the cloud required additional problem-solving.  

---

## 4. Key Achievements
- Built a **complete cloud-based CV generation system** using AWS.  
- Successfully generated and distributed PDFs using **Puppeteer, S3, and CloudFront**.  
- Designed a **scalable cloud architecture**.  
- Gained a **new set of technical skills** for future projects.  

---

## 5. Reflection & Learning
- Learned a lot of new skills and applied existing AWS knowledge.  
- Improved **problem-solving skills, patience, and cloud expertise**.  
- Confirmed that **cloud services** are the area I want to focus on in my career.  

---

## 6. Future Goals
- Focus mainly on **cloud services** rather than traditional programming tasks.  
- Aim to work in roles like **cloud architect or cloud consultant**.  
- Continue improving technical skills, gaining work experience, and completing **AWS certifications**.  

---

## 7. Why These Documents
I chose these materials for my portfolio because they clearly show:  
- My work on the project.  
- My learning process and skill development.  
- The challenges I faced while building a cloud-based application.  
