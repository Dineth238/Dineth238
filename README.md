<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GitHub Profile</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Hey there, I'm <span id="name">Dineth Ravindu</span>! 👨‍💻🚀</h1>
        <p id="typing"></p>
        <img src="https://your-image-link.com" alt="Profile Banner">
    </header>
    
    <section>
        <h2>👨‍💻 About Me</h2>
        <ul>
            <li>🎓 <strong>BSc Honours in Business Information Systems Degree</strong> at <strong>University of Sri Jayewardenepura</strong></li>
            <li>💡 Always learning new technologies</li>
            <li>💻 Writing <strong>clean, efficient, and scalable code</strong></li>
            <li>📌 Open to collaborations, freelance projects, and new opportunities!</li>
        </ul>
    </section>
    
    <section>
        <h2>🚀 Tech Stack</h2>
        <div class="tech">
            <span>Python</span>
            <span>JavaScript</span>
            <span>C++</span>
            <span>Flutter</span>
            <span>GitHub</span>
            <span>VS Code</span>
        </div>
    </section>
    
    <section>
        <h2>📊 GitHub Stats & Contributions</h2>
        <img src="https://github-readme-streak-stats.herokuapp.com/?user=Dineth238&theme=radical" alt="GitHub Streak">
        <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Dineth238&layout=compact&theme=radical" alt="Top Languages">
        <img src="https://github-readme-activity-graph.vercel.app/graph?username=Dineth238&theme=react-dark" alt="GitHub Activity Graph">
    </section>
    
    
    <section>
        <h2>📫 Connect with Me</h2>
        <a href="https://linkedin.com/in/yourusername">LinkedIn</a>
        <a href="https://twitter.com/yourusername">Twitter</a>
    </section>
    
    <script>
        const words = ["Coding is my passion!", "I love solving problems with code!", "Building cool stuff every day! 🚀"];
        let i = 0;
        const typingElement = document.getElementById("typing");
        function type() {
            typingElement.textContent = words[i];
            i = (i + 1) % words.length;
            setTimeout(type, 2000);
        }
        type();
    </script>
</body>
</html>
