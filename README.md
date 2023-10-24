# maven-notes

# What is maven
- Is a build tool for java that maintains third-party libraries like (API, JAR, Dependencies) in pom.xml file.

# Why use maven?
##### Problem: When creating a project that needs third-party libraries we tend to find all the related dependency and download it manually from diff websites then we add it in classpath which every java developer struggles for the first time and then we face issue of versioning incompatible and lack of required dependencies to for that third-party library to work.

##### Solution: Thats why we use maven, maven uses cdn like to download all required dependecies and help manage the versioning of each dependencies of your project.

# What is pom.xml
- This is the file where you manage your dependecies.
- pom stands for **Project Object Model**
- xml stands for **Extensive Markup Languange**.

### Parts of pom.xml
- **Dependecies**: This where you put the dependecies and third-party libraries from maven repository. For maven to manage it.
  
- **Plugins**: This is where you put the extra settings and configuration needed for your dependecies or third-party library to work. It controls the project.

- **Properties**: This is where you put the variables used in you're dependecies and plugins. example the versioning of youre dependecies.

# What is maven archytype?
- Is a project that has default dependecies for you to work faster that they also configured the required dependecies amd versioning.
- You can think of this as template.

# How to create maven project
- **group id**: name of the company or individual.
- **artifact id**: name of the project.
##### Will produce com.elleined.myproject

# Where to get the dependecies and third-party libraries.
[Maven Repository](https://mvnrepository.com/)
