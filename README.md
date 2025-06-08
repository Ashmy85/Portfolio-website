<!DOCTYPE html>
<html lang="en">
<head>
       <title>Ashmy Philo Joji - Resume</title>
    <style>
        :root {
            --primary-color: #4b6cb7;
            --secondary-color: #182848;
            --accent-color: #f85f73;
            --light-color: #f8f9fa;
            --dark-color: #343a40;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            
        }
        
        body {
            line-height: 1.6;
            color: var(--dark-color);
            background-color: var(--light-color);
        }
        
        .container {
            max-width: 900px;
            margin: 0 auto;
            padding: 20px;
        }
        
        header {
            background: linear-gradient(135deg, var(--primary-color), var(--secondary-color));
            color: white;
            padding: 40px 20px;
            text-align: center;
            border-radius: 0 0 10px 10px;
            box-shadow: 0 4px 12px rgba(0,0,0,0.1);
        }
        
        .profile-img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            object-fit: cover;
            border: 4px solid white;
            margin-bottom: 20px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.2);
        }
        
        h1 {
            font-size: 2.5rem;
            margin-bottom: 10px;
        }
        
        .tagline {
            font-size: 1.2rem;
            opacity: 0.9;
        }
        
        section {
            background: white;
            margin: 30px 0;
            padding: 30px;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.05);
        }
        
        h2 {
            color: var(--primary-color);
            margin-bottom: 20px;
            padding-bottom: 10px;
            border-bottom: 2px solid var(--primary-color);
        }
        
        .education-item, .experience-item {
            margin-bottom: 25px;
        }
        
        .item-header {
            display: flex;
            justify-content: space-between;
            margin-bottom: 8px;
        }
        
        .item-title {
            font-weight: bold;
            font-size: 1.1rem;
        }
        
        .item-date {
            color: var(--accent-color);
            font-weight: bold;
        }
        
        .item-subtitle {
            color: #666;
            margin-bottom: 8px;
        }
        
        .skills-container {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
        }
        
        .skill {
            background-color: var(--primary-color);
            color: white;
            padding: 6px 12px;
            border-radius: 20px;
            font-size: 0.9rem;
        }
        
        .interests-container {
            display: flex;
            flex-wrap: wrap;
            gap: 15px;
        }
        
        .interest {
            display: flex;
            flex-direction: column;
            align-items: center;
            width: 80px;
        }
        
        .interest-icon {
            font-size: 2rem;
            color: var(--accent-color);
            margin-bottom: 8px;
        }
        
        footer {
            text-align: center;
            padding: 20px;
            color: #666;

            font-size: 0.9rem;
        }
        
        {
            .item-header {
                flex-direction: column;
            }
            
            .item-date {
                margin-top: 5px;
            }
        }
    </style>
    
</head>
<body>
    <header>
        <h1>Ashmy Philo Joji</h1>
        <p class="tagline">Computer Science Student | Creative Enthusiast | Explorer</p>
    </header>

    
    <div class="container">
        <section id="about">
            <h2>About Me</h2>
            <p>
                A passionate Computer Science student currently pursuing B.Tech at Amal Jyothi College of Engineering, Kanjirappally.
                Originally from Kanjirappally, Kottayam , Kerala, I have a strong academic background  from St.Antony's Public School
                .Beyond academics, I'm deeply interested in photography, public speeking, dancing and music. I love traveling and exploring new experiences.
            </p>
        </section>
        
        <section id="education">
            <h2>Education</h2>
            <div class="education-item">
                <div class="item-header">
                    <span class="item-title">B.Tech in Computer Science</span>
                    <span class="item-date">2024 - Present</span>
                </div>
                <div class="item-subtitle">Amal Jyothi College of Engineering, Kanjirappally</div>
                <p>Currently in S2 with excellent academic performance</p>
            </div>
            
            
        </section>
        
        <section id="skills">
            <h2>Skills</h2>
            <div class="skills-container">
                <span class="skill">Programming</span>
                <span class="skill">Web Development</span>
                <span class="skill">Photography</span>
                <span class="skill">Digital Art</span>
                <span class="skill">Creative Writing</span>
                <span class="skill">Problem Solving</span>
                <span class="skill">Teamwork</span>
            </div>
        </section>
        
        <section id="interests">
            <h2>Interests & Hobbies</h2>
            <div class="interests-container">
                <div class="interest">
                    <i class="fas fa-camera interest-icon"></i>
                    <span>Photography</span>
                </div>
                <div class="interest">
                    <i class="fas fa-paint-brush interest-icon"></i>
                    <span>Painting</span>
                </div>
                <div class="interest">
                    <i class="fas fa-music interest-icon"></i>
                    <span>Music</span>
                </div>
                <div class="interest">
                    <i class="fas fa-plane interest-icon"></i>
                    <span>Travel</span>
                </div>
                <div class="interest">
                    <i class="fas fa-laptop-code interest-icon"></i>
                    <span>Technology</span>
                </div>
                <div class="interest">
                    <i class="fas fa-book interest-icon"></i>
                    <span>Reading</span>
                </div>
            </div>
        </section>
    </div>
    
    <footer>
        <p>&copy; 2025 Ashmy Philo Joji | kanjirappally, Kottayam , Kerala</p>
    </<ul>
<li>LinkedIn: <a href=https://www.linkedin.com/in/ashmy-philo-joji-b966a7326?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app>LinkedIn</a> </li>
</footer>
    

</body>
</html>
