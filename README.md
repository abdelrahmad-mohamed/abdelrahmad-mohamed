from pathlib import Path

content = r'''<div align="center">

# Hi, I'm Abdelrahman Fathi 👋

### Software Engineer | Backend .NET Developer

I build practical software solutions and enjoy understanding how systems work — from databases and APIs to application architecture.

<p>
  <a href="mailto:2abdelrhman00mohamed4@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact%20me-0A66C2?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <!-- Replace YOUR_LINKEDIN_URL with your LinkedIn profile URL -->
  <a href="YOUR_LINKEDIN_URL">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
</p>

</div>

---

## 👨‍💻 About Me

I'm a Computer Science graduate from the **Arab Open University (Egypt)**, focused on **backend development with C# and ASP.NET Core**.

- 🔧 I work with **C#, .NET, SQL Server, Entity Framework Core, and LINQ**.
- 🧱 I'm strengthening my knowledge of **Web APIs, SOLID principles, design patterns, and system design**.
- 🗃️ I enjoy learning how databases work under the hood, including query execution and optimization.
- 🤝 I've worked across software development, Power Platform, and collaborative project work.
- 🚀 My goal is to become a stronger engineer who can design, build, and maintain reliable software — not just make it work.

## 🛠️ Tech Stack

### Backend & Databases
<p>
  <img src="https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=csharp&logoColor=white" alt="C sharp" />
  <img src="https://img.shields.io/badge/.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white" alt=".NET" />
  <img src="https://img.shields.io/badge/ASP.NET_Core-512BD4?style=flat-square&logo=dotnet&logoColor=white" alt="ASP.NET Core" />
  <img src="https://img.shields.io/badge/Entity_Framework_Core-512BD4?style=flat-square&logo=dotnet&logoColor=white" alt="Entity Framework Core" />
  <img src="https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white" alt="SQL Server" />
  <img src="https://img.shields.io/badge/LINQ-512BD4?style=flat-square&logo=dotnet&logoColor=white" alt="LINQ" />
</p>

### Tools & Other Technologies
<p>
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git" />
  <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub" />
  <img src="https://img.shields.io/badge/Power_Apps-742774?style=flat-square&logo=powerapps&logoColor=white" alt="Power Apps" />
  <img src="https://img.shields.io/badge/Power_Automate-0066FF?style=flat-square&logo=powerautomate&logoColor=white" alt="Power Automate" />
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white" alt="CSS3" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript" />
</p>

## 💼 Experience & Training

| Organization | Role / Program | Focus |
|---|---|---|
| **Nefertari Tiba Manzalawi** | Software Engineer | Software development and digital solutions |
| **Global Brands Group** | Backend ASP.NET Intern | Backend development with ASP.NET |
| **Global Brands Group** | Power Apps Trainee | Business applications and Power Platform |
| **Information Technology Institute (ITI)** | .NET Trainee — Summer Code Camp | .NET development fundamentals |
| **Digital Egypt Pioneers Initiative (DEPI)** | AI & Data Science Trainee | AI and data science foundations |
| **Orange Digital Center / DEPI** | Machine Learning Training | Machine learning fundamentals |



<div align="center">

### Thanks for visiting my profile!

*Always learning. Always building. Always improving.*

</div>
'''

path = Path("/mnt/data/README_GitHub_Profile.md")
path.write_text(content, encoding="utf-8")
print(f"Created: {path}")
