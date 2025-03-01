# MyPortfolio
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Website</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="projects.html">Projects</a></li>
                <li><a href="login.html">Login</a></li>
                <li><button onclick="logout()">Logout</button></li>
            </ul>
        </nav>
    </header>
    <section class="intro">
        <h1>Welcome to My Website</h1>
        <p>Hi, I'm Roshni. This is my personal website where you can find my projects and resume.</p>
        <a href="resume.pdf" target="_blank" class="resume-btn">View My Resume</a>
    </section>
    
<script>
        function logout() {
            window.location.href = "exit.html";
        }
</script>
</body>
</html>

