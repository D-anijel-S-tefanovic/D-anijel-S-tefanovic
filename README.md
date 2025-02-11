### Hi there 👋  

I am a passionate Software Developer/Data Engineer based in Toronto, ON, Canada.  

## Connect With Me
[<img align="left" alt="linkedin" src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" />](https://www.linkedin.com/in/danijel-stefanovic/)
[<img align="left" alt="stack-overflow" src="https://img.shields.io/badge/stack%20overflow-222426.svg?&style=for-the-badge&logo=stackoverflow" />](https://stackoverflow.com/story/danijel-stefanovic)

<br>  
<br>
  
## To Find Out More About My Skills 

// Hi there, I'm [Your Name] 👋

class DeveloperIntroduction {
  name: string;
  skills: string[];
  focusAreas: string[];
  projects: string[];

  constructor() {
    this.name = "[Your Name]";
    this.skills = ["TypeScript", "JavaScript", "React", "Node.js"]; // Add your skills here
    this.focusAreas = ["Efficient Code", "Scalability", "Performance Optimization"];
    this.projects = ["Personal Projects", "Open Source Contributions"];
  }

  greet(): void {
    console.log(`Hello! I'm ${this.name}, a passionate Software Developer. 👨‍💻`);
  }

  shareSkills(): void {
    console.log("I specialize in:");
    this.skills.forEach(skill => console.log(`- ${skill}`));
  }

  shareFocusAreas(): void {
    console.log("I focus on:");
    this.focusAreas.forEach(area => console.log(`- ${area}`));
  }

  shareProjects(): void {
    console.log("Check out my projects:");
    this.projects.forEach(project => console.log(`- ${project}`));
  }

  intro(): void {
    this.greet();
    this.shareSkills();
    this.shareFocusAreas();
    this.shareProjects();
  }
}

const myIntro = new DeveloperIntroduction();
myIntro.intro();
