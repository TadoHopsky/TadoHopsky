```java
public class GitHubProfile {
    
    // About me
    private String name = "Tado Hopsky";
    private String title = "Java Backend Developer | Open-Source Enthusiast";
    private String[] skills = {"Java","Python", "Golang", "HTML", "CSS", "Git", "SQL"};
    
    // Contact information
    private String email = "frolov.dev1375@yandex.ru";
    private String tekegram = "@tadohopsky";
    private String github = "https://github.com/TadoHopsky";

    public GitHubProfile() {
        printWelcomeMessage();
        showSkills();
        showProjects();
        showContactInfo();
    }

    // Print welcome message
    private void printWelcomeMessage() {
        System.out.println("Hello, World! Welcome to my GitHub profile.");
        System.out.println("I am a passionate developer always eager to learn new technologies.");
    }

    // Display list of skills
    private void showSkills() {
        System.out.println("\n🛠️ Skills:");
        for (String skill : skills) {
            System.out.println("- " + skill);
        }
    }

    // Display contact information
    private void showContactInfo() {
        System.out.println("\n📬 Contact Me:");
        System.out.println("Email: " + email);
        System.out.println("LinkedIn: " + linkedin);
        System.out.println("GitHub: " + github);
    }

    // Main method to run the program (i.e., the profile!)
    public static void main(String[] args) {
        new GitHubProfile();
    }
}
