```java

/**
 * @author Lilian Mirabel
 * @version 2026.10
 * @description Master's Student in Software Architecture @ Université de La Rochelle
 */
public class LilianMirabel extends SoftwareDeveloper implements PassionateBuilder {

    private final String name = "Lilian Mirabel";
    private final String location = "La Rochelle & Lyon, France ";
    private final String status = "Master 2 Student in Software Architecture";
    private final String currentRole = "IT Engineering Apprentice / Java Developer @ SNCF Voyageurs (Lyon)";
    
    // 🔧 Tech Stack
    private final List<String> frontend = List.of("React", "Vue", "Angular", "TypeScript");
    private final List<String> mobile = List.of("React Native", "Expo", "Swift");
    private final List<String> backend = List.of("Java", "Python", "C++", "PHP", "Spring Boot");
    private final List<String> tools = List.of("Clean Architecture", "Git", "Docker", "CI/CD");

    // 🏗️ Featured Projects
    private final Map<String, String> projects = Map.of(
        "🏈 Gaulois", "Open-source app to track a football team's matches & players",
        "🎧 FestivApp", "Mobile application listing festivals across mainland France",
        "🧬 DiagnoSphere", "Medical monitoring tool designed for research use"
    );

    @Override
    public void code() {
        while (isCurious && motivated) {
            solveRealWorldProblems();
            focusOnCodeQuality();
            enjoyDeveloperExperience();
        }
    }

    public void getInTouch() {
        String email = "lilianmirabel01120@gmail.com";
        System.out.println("Let's connect: " + email);
    }

    public void getWebsite() {
        String web = "lilianmirabel.fr";
        System.out.println("My Website: " + web);
    }
}
```
