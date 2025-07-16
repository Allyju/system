# system
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>M_in_X.Tech | eLearning Platform</title>
    <style>
        :root {
            --primary: #4f46e5;
            --dark: #1e293b;
            --light: #f8fafc;
            --gray: #94a3b8;
        }
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: 'Inter', sans-serif;
            line-height: 1.6;
            color: var(--dark);
            background-color: var(--light);
        }
        .container {
            width: 90%;
            max-width: 1200px;
            margin: 0 auto;
        }
        header {
            background: white;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
            padding: 1rem 0;
            position: sticky;
            top: 0;
            z-index: 100;
        }
        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        .logo {
            font-size: 1.5rem;
            font-weight: 700;
            color: var(--dark);
        }
        .logo span {
            color: var(--primary);
        }
        .nav-links a {
            margin-left: 1.5rem;
            color: var(--dark);
            text-decoration: none;
            font-weight: 500;
        }
        .hero {
            padding: 5rem 0;
            text-align: center;
        }
        .course-card {
            background: white;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
            overflow: hidden;
            margin-bottom: 2rem;
        }
        .course-card img {
            width: 100%;
            height: 200px;
            object-fit: cover;
        }
        .course-info {
            padding: 1.5rem;
        }
        .btn {
            display: inline-block;
            background: var(--primary);
            color: white;
            padding: 0.8rem 1.5rem;
            border-radius: 4px;
            text-decoration: none;
            font-weight: 600;
            margin-top: 1rem;
        }
        footer {
            background: var(--dark);
            color: white;
            padding: 2rem 0;
            text-align: center;
        }
        @media (max-width: 768px) {
            nav {
                flex-direction: column;
            }
            .nav-links {
                margin-top: 1rem;
            }
            .nav-links a {
                margin: 0 0.5rem;
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <nav>
                <div class="logo">M_in_X.<span>Learn</span></div>
                <div class="nav-links">
                    <a href="#courses">Courses</a>
                    <a href="#features">Features</a>
                    <a href="#contact">Contact</a>
                    <a href="#" class="btn">Sign In</a>
                </div>
            </nav>
        </div>
    </header>

    <section class="hero">
        <div class="container">
            <h1>Learn Tech Skills Online</h1>
            <p>Master programming, web development, and software design with our interactive courses</p>
            <a href="#courses" class="btn">Browse Courses</a>
        </div>
    </section>

    <section id="courses" class="container" style="padding: 3rem 0;">
        <h2 style="text-align: center; margin-bottom: 2rem;">Popular Courses</h2>
        <div class="course-card">
            <img src="https://via.placeholder.com/800x400?text=Web+Development" alt="Web Development">
            <div class="course-info">
                <h3>Modern Web Development</h3>
                <p>Learn HTML, CSS, JavaScript and frameworks like React and Node.js</p>
                <a href="#" class="btn">Enroll Now</a>
            </div>
        </div>
        <div class="course-card">
            <img src="https://via.placeholder.com/800x400?text=Python+Programming" alt="Python Programming">
            <div class="course-info">
                <h3>Python Programming</h3>
                <p>From basics to advanced Python concepts and Django framework</p>
                <a href="#" class="btn">Enroll Now</a>
            </div>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2023 M_in_X.Tech eLearning Platform</p>
        </div>
    </footer>
</body>
</html>
```
