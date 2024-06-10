# Hi there! 👋 Welcome to my profile!
[![Uipath](https://img.shields.io/badge/Uipath-orange?style=for-the-badge&logo=Uipath&logoColor=white&labelColor=101010)](https://docs.uipath.com/studio/standalone/2023.10/user-guide/introduction)
[![C#](https://img.shields.io/badge/csharp-5646ED?style=for-the-badge&logo=csharp&logoColor=white&labelColor=101010)](https://dotnet.microsoft.com/es-es/languages/csharp)
[![HTML](https://img.shields.io/badge/HTML-yellow?style=for-the-badge&logo=html5&logoColor=white&labelColor=101010)](https://developer.mozilla.org/es/docs/Web/HTML)
[![CSS](https://img.shields.io/badge/CSS-blue?style=for-the-badge&logo=css3&logoColor=white&labelColor=101010)](https://developer.mozilla.org/es/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-yellow?style=for-the-badge&logo=javascript&logoColor=white&labelColor=101010)](https://developer.mozilla.org/es/docs/Web/JavaScript)
[![.NET](https://img.shields.io/badge/.net-5646ED?style=for-the-badge&logo=.net&logoColor=white&labelColor=101010)](https://developer.mozilla.org/es/docs/Web/JavaScript)
[![PHP](https://img.shields.io/badge/php-green?style=for-the-badge&logo=php&logoColor=white&labelColor=101010)](https://developer.mozilla.org/es/docs/Web/JavaScript)

I'm a passionate Software Engineer with expertise in automating processes using UiPath Studio and developing robust applications with SQL, C#, Java, and JavaScript. 
I also have experience with version control using GitHub and cloud computing with Google Cloud.
## About Me
I love solving complex problems and turning ideas into efficient solutions. 
With a keen eye for detail and a drive for continuous learning, 
I strive to deliver high-quality software that exceeds expectations.

![Robot](https://github.com/ramirezxc02/ramirezxc02/blob/main/image.jpg)

## Experience
 **Software Engineer/RPA Specialist** at Equifax (2022 - Present) 🐱‍💻
  - Collaborate with stakeholders to gather feedback on existing automation solutions and identify areas for improvement.
  - Respond to user inquiries and support tickets related to bot operation, functionality, or performance.
  - Investigate and resolve issues reported by users or detected through monitoring tools.
  - Apply patches, updates, and enhancements to the automation solution to address bugs, improve reliability, or incorporate new features.
  - Configure bot settings, such as triggers, inputs, outputs, error handling, and security permissions.
  - Test the automation solution to ensure it performs as expected and meets the defined criteria.

  **Volunteer WordPress Developer** at AIESEC  (2021)
  - Install and configure WordPress on web servers, including database setup and file permissions.
  - Customize WordPress settings, including permalinks, user roles, and media settings.
  - Configure site-wide settings such as SEO, caching, and security measures.
  - Install and configure necessary plugins and themes based on project requirements.

 **Full-Stack Developer** at Facture CR (2020) 🐱‍👤
  - Conduct frontend testing, including unit testing and end-to-end testing, to ensure functionality and compatibility across browsers and devices.
  - Implement user interface designs ensuring consistency and adherence to design guidelines.
  - Integrate frontend components with backend APIs to fetch and display dynamic data.
  - Conduct frontend testing, including unit testing and end-to-end testing, to ensure functionality and compatibility across browsers and devices.
    
# Projects 🧨

 #### **ISLAPP** 
 This was one of my last university projects, and I'm really proud of it. This was created for "San Lucas Island" employers to automate the way that they stored the ilicit activities made by whoever which was visiting the island. The main technologies used for developing thi project were:
 -C#, .Net Framework, GitHub, SQL server and the architecture was "Multi-Layers". ![Link](https://github.com/ramirezxc02/ISLApp.git)
 
 ![Robot](https://github.com/ramirezxc02/ramirezxc02/blob/main/Interface_Islapp.png)

 ``` Ruby
public void registrarReporte()
        {
        try{
            if (this.validarEspaciosEnBlanco())
                {
                    this.conexion.registrarReporte(crearReporte());
                    MessageBox.Show("Reporte registrado correctamente.", "Proceso aplicado", MessageBoxButtons.OK, MessageBoxIcon.Information);
                    this.limpiarTexBox();
                }
            }catch (Exception e)
            {
                MessageBox.Show(e.Message);
            }
        }
```
#### **Referrals** 
This is a company process, I can't give too much detailes due to company policies but it's an automation which take decisions based on information obtained from Images. I didn't develop this one but I added some Improvements, one of them was consume information from GCP buckets. The technologies on this projects are:
⭐Uipath Studio
⭐SQL Server
⭐BigQuery
⭐Analytics
⭐GCP
⭐Google Vision.

 ![Bucket](https://github.com/ramirezxc02/ramirezxc02/blob/main/Bucket_Sequence.jpg)

 ### **Referrals Bucket Module Test Case example** ✔
 
 ![Bucket]( https://github.com/ramirezxc02/ramirezxc02/blob/main/GCS_Bucket_TestCase.jpg)


#### **DD-Bot** This is an internal bot. It helps our team to distribuite the other bots. 🤖
+ Process:
  1.Create a call to get current volumes and show them to the user by using the API from Orchestrator.
  2. Receive an input which are the amount of bots to assign.
  3. Send the new distribution using the API again. The technologies on this projects are: Uipath Studio,Uipath Orchestrator API, Uipath Forms, we also used json structure form payloads.
  
 ![RobotBebe](https://github.com/ramirezxc02/ramirezxc02/blob/main/polifolli-robot.gif)

 ✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨
# **Automated Password bot** 😎 In progress...
   This is an internal bot which will be in charge of update bots with the new password. This is necessary because we have to update more than 70 accounts 2 times per month.😥
   This Bot interact with a internal platform where the new password is created and with orchestrator which is the place where the assets are located. This will contribute to the D2C support team.
   
   ![Pacman](https://github.com/ramirezxc02/ramirezxc02/blob/main/Pacman.gif)
   
## Best Practices 🎉
- **Clean Code Advocate:** I believe in writing clean, maintainable code following industry best practices to enhance readability and scalability.
- **Agile Enthusiast:** Proficient in Agile methodologies, I thrive in fast-paced environments and adapt quickly to changing requirements.
- **Modularize Code:** Break down the codebase into smaller, reusable modules or components. Modular code promotes code reusability, scalability, and testability, making it easier to manage and maintain.
- **Understand Requirements Thoroughly:** Before starting development, ensure a comprehensive understanding of the project requirements. Clarify any ambiguities and communicate effectively with stakeholders to align expectations.
- **Stay Updated with Technology:** Keep abreast of emerging technologies, tools, and best practices relevant to your field. Continuous learning and professional development help you stay competitive and adapt to evolving industry trends.
- **Optimize Performance:** Identify and address performance bottlenecks through profiling, optimization techniques, and efficient algorithms. Optimizing performance ensures that the software meets scalability and responsiveness requirements.

## Technical Skills 🎇
- **Automation Tools:** UiPath Studio
- **Programming Languages:** C#, Java, JavaScript
- **Database Management:** SQL
- **Version Control:** GitHub
- **Cloud Computing:** Google Cloud

## Soft Skills 🤝🏼
- **Communication:** Effective communicator able to convey technical concepts to non-technical stakeholders.
- **Problem-Solving:** Strong analytical skills with a knack for identifying and solving complex problems.
- **Team Player:** Collaborative team member who fosters a positive and inclusive work environment.

# Q&A ❓

Feel free to reach out to me via [email](henoly.ramirez@equifax.com) for collaborations or exciting opportunities! Let's connect on [LinkedIn](www.linkedin.com/in/henoly-ramírez-575745203) too!
