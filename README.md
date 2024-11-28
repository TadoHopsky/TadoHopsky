<!-- README.md -->
<h1 align="center">✨ Welcome to My GitHub ✨</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Java-Spring%20Boot-green?style=for-the-badge" alt="Java">
  <img src="https://img.shields.io/badge/Thymeleaf-Templates-blue?style=for-the-badge" alt="Thymeleaf">
  <img src="https://img.shields.io/badge/Docker-Containers-blue?style=for-the-badge" alt="Docker">
</p>

<br>

<div align="center">
  <pre style="text-align: left; background-color: #1e1e1e; color: #dcdcdc; padding: 20px; font-family: 'Courier New', Courier, monospace; font-size: 16px; border-radius: 8px; box-shadow: 0 4px 6px rgba(0, 0, 0, 0.2); width: 80%;">
    <code id="animated-code">
public class GitHubProfile {

    public static void main(String[] args) {
        Developer me = new Developer(
            "Your Name",
            List.of("Java", "Spring Boot", "Thymeleaf", "Docker"),
            "Creating elegant and scalable solutions"
        );

        me.displaySkills();
        me.displayProjects();
        me.displayContact();
    }

    static class Developer {
        private String name;
        private List<String> skills;
        private String mission;

        public Developer(String name, List<String> skills, String mission) {
            this.name = name;
            this.skills = skills;
            this.mission = mission;
        }

        public void displaySkills() {
            System.out.println("🛠️ Skills: " + skills);
        }

        public void displayProjects() {
            System.out.println("\n🌟 Featured Projects:");
            System.out.println("- Spring Boot API");
            System.out.println("- Thymeleaf Dashboard");
            System.out.println("- Java Algorithms");
        }

        public void displayContact() {
            System.out.println("\n📫 Contact me:");
            System.out.println("- Email: yourname@example.com");
            System.out.println("- LinkedIn: linkedin.com/in/yourname");
            System.out.println("- Blog: yourwebsite.com");
        }
    }
}
    </code>
  </pre>
</div>

<script>
const codeLines = `
public class GitHubProfile {

    public static void main(String[] args) {
        Developer me = new Developer(
            "Your Name",
            List.of("Java", "Spring Boot", "Thymeleaf", "Docker"),
            "Creating elegant and scalable solutions"
        );

        me.displaySkills();
        me.displayProjects();
        me.displayContact();
    }

    static class Developer {
        private String name;
        private List<String> skills;
        private String mission;

        public Developer(String name, List<String> skills, String mission) {
            this.name = name;
            this.skills = skills;
            this.mission = mission;
        }

        public void displaySkills() {
            System.out.println("🛠️ Skills: " + skills);
        }

        public void displayProjects() {
            System.out.println("\\n🌟 Featured Projects:");
            System.out.println("- Spring Boot API");
            System.out.println("- Thymeleaf Dashboard");
            System.out.println("- Java Algorithms");
        }

        public void displayContact() {
            System.out.println("\\n📫 Contact me:");
            System.out.println("- Email: yourname@example.com");
            System.out.println("- LinkedIn: linkedin.com/in/yourname");
            System.out.println("- Blog: yourwebsite.com");
        }
    }
}`;
