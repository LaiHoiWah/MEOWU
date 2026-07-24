## MEOWU

### Project Summary
1. The word **MEOWU** originates from the sound of a little cat that used to live in my home. To commemorate its years of companionship, I created the word **MEOWU** as the name for this project.
2. This project is currently not publicly available and is solely for personal learning purposes.

---

### Project Conventions
1. Naming conventions
   - Component-type projects should be prefixed with **meowu-starter-**
   - API service-type projects should be prefixed with **meowu-svc-**
   - Management platform projects (backend) should be prefixed with **meowu-svc-platform-**
   - Management platform projects (frontend) should be prefixed with **meowu-app-web-**
   - Application-type projects (backend) should be prefixed with **meowu-svc-app-**
   - Application-type projects (frontend) should be prefixed with **meowu-app-mobile-**
2. Package Naming Conventions
   - Package names must be named in the format **com.meowu.[projectType].[projectName]**
3. Package Structure Conventions
   - The **commons** package is intended for common classes, including utilities, configurations, constants, and the like
   - The **commons.security** package is intended for exceptions, responses, security management, and related concerns.
   - The **core** package is intended for the primary business logic code of the project.
4. Maven Group
   - GroupId: **com-meowu**
   - ArtifactId: **[projectType]-[projectName]**
   
---

### Project Map
1. Commons List 

| Name                           | Usage                         |
|:-------------------------------|:------------------------------|
| com-meowu-starter-dependencies | Parent Dependencies pom       |
| com-meowu-starter-commons      | Commons package               |
| com-meowu-starter-jpa          | JPA plugin                    |
| com-meowu-starter-web          | Web Component                 |
| com-meowu-starter-security     | Application Security Component|