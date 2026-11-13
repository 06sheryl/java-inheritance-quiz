# Java Inheritance Interactive Knowledge Check

A mobile-friendly, standalone five-question quiz for Java OOP inheritance. No dependencies, server, or student accounts required.

## Publish with GitHub Pages

1. Create a new **public** GitHub repository, such as `java-inheritance-quiz`.
2. Upload `index.html` to the **root** of the repository and commit.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, then select **main** and **/(root)** and click **Save**.
5. Wait for GitHub Pages deployment. The typical URL format is `https://YOUR-USERNAME.github.io/java-inheritance-quiz/`.

## Customize

- Edit the `questions` array in `index.html` to change questions, answers, and explanations.
- Edit the `footer` element to change the attribution.
- Colors are controlled by CSS variables at the top of the `<style>` section.

## Privacy and limitations

All grading happens in the student's browser. No student information is transmitted to a backend or collected by the teacher. Students can print or save their result as a PDF and submit it separately. Scores are not tamper-proof; this is intended for formative practice, not secure examinations.

## Java nuance

Question 4 specifies that `Animal` is a class and `Swimmer` and `Flyer` are interfaces, avoiding ambiguous options. Question 5 uses the common teaching label *hybrid inheritance* for class inheritance combined with multiple interfaces; Java itself has no dedicated `hybrid` keyword.
