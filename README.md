<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>GitHub Profile</title>
  <style>
    body {
      font-family: 'Arial', sans-serif;
      background-color: #f5f5f5;
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    header {
      background-color: #24292e;
      color: #ffffff;
      text-align: center;
      padding: 20px;
    }

    main {
      max-width: 800px;
      margin: 20px auto;
      padding: 20px;
      background-color: #ffffff;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
      border-radius: 8px;
    }

    h1,
    h2,
    h3 {
      color: #24292e;
    }

    .card {
      background-color: #f0f0f0;
      border: 1px solid #ddd;
      border-radius: 8px;
      padding: 20px;
      margin: 15px 0;
    }

    .project-card {
      display: flex;
      flex-direction: column;
      gap: 15px;
    }

    .project-details {
      display: flex;
      flex-wrap: wrap;
      gap: 15px;
    }

    .project-details img {
      max-width: 100%;
      height: auto;
    }

    .achievements {
      background-color: #28a745;
      color: #ffffff;
      padding: 15px;
      border-radius: 8px;
    }
  </style>
</head>

<body>
  <header>
    <h1>Hi there! 👋 I'm [Your Name]</h1>
  </header>

  <main>
    <section id="summary">
      <h2>Summary</h2>
      <p>I am passionate about technology and aspire to be part of an organization where I can continuously develop my technical and management skills. My goal is to contribute to the growth and success of the organization.</p>
    </section>

    <section id="technical-skills" class="card">
      <h2>Technical Skills</h2>
      <ul>
        <li><strong>Programming Languages:</strong> C, C++, JavaScript</li>
        <li><strong>Web Technologies:</strong> HTML5, CSS, Bootstrap</li>
        <li><strong>Data Management:</strong> MySQL</li>
        <li><strong>Platform:</strong> Windows</li>
      </ul>
    </section>

    <section id="certifications" class="card">
      <h2>Certifications</h2>
      <ul>
        <li>Introduction to Front-end Development by Coursera (Sep'22)</li>
        <li>Programming with JavaScript by Coursera (Oct'22)</li>
        <li>Version Control by Coursera (Nov'22)</li>
      </ul>
    </section>

    <section id="power-skills" class="card">
      <h2>Power Skills</h2>
      <ul>
        <li>Strong problem-solving and analytical abilities</li>
        <li>Effective communication and teamwork</li>
      </ul>
    </section>

    <section id="extracurricular-activities" class="card">
      <h2>Extracurricular Activities</h2>
      <ul>
        <li>Competitive event on "Follow the Leader" (Aug'22)</li>
        <li>Community Development Program on "Adopt a Plant" (Jul'22)</li>
      </ul>
    </section>

    <section id="projects" class="card">
      <h2>Projects</h2>

      <div class="project-card">
        <div class="project-details">
          <img src="https://placekitten.com/300/200" alt="Farming Website Screenshot">
          <p>Created using HTML5, CSS, JavaScript, and Bootstrap. Provides basic information on farming for beginners. Features a product page with seeds for sale. Enhanced understanding of advanced JavaScript concepts and Bootstrap library.</p>
        </div>
      </div>

      <div class="project-card">
        <div class="project-details">
          <img src="https://placekitten.com/300/200" alt="Covid 19 Cure Website Screenshot">
          <p>Developed with HTML5, CSS, JavaScript, and Bootstrap. Displays vaccination statistics for India and worldwide. Shows locations available for vaccination with booking options. Learned CSS flex-box, Bootstrap grid, and JavaScript event handling.</p>
        </div>
      </div>

      <div class="project-card">
        <div class="project-details">
          <img src="https://placekitten.com/300/200" alt="Calculator Screenshot">
          <p>Built with HTML5, CSS, and JavaScript. Basic calculator supporting all mathematical operators. Enhanced user interface using CSS and improved functionality with JavaScript.</p>
        </div>
      </div>

    </section>

    <section id="achievements" class="achievements">
      <h2>Achievements</h2>
      <p>1st Rank in the competition on 'Follow the Leader' (Aug'22)</p>
    </section>

    <section id="education" class="card">
      <h2>Education</h2>
      <ul>
        <li><strong>Bachelor of Computer Application</strong> (2019 - Present)<br>Lovely Professional University, Phagwara (Punjab)<br>CGPA: 6.5</li>
        <li><strong>Higher Secondary</strong> (2019)<br>Delhi Public School, Lagma (Bihar)</li>
      </ul>
    </section>
  </main>
</body>

</html>
