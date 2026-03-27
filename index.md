---
layout: default
title: Adrian Lozada
---

<section class="hero" id="about">
  <div class="container">
    <div class="hero-content">
      <h1>Adrian Lozada</h1>
      <p class="hero-subtitle">M.S. Computational Science & Engineering @ Georgia Tech</p>
      <p class="hero-description">I build high-performance computing systems, parallel algorithms, and intelligent software. My work spans HPC, distributed systems, robotics, and machine learning.</p>
      <div class="hero-actions">
        <a href="files/resume.pdf" class="btn btn-primary" target="_blank">View Resume</a>
        <a href="#experience" class="btn btn-outline">See My Work</a>
      </div>
    </div>
  </div>
</section>

<section class="section" id="experience">
  <div class="container">
    <h2 class="section-title">Experience</h2>

    <div class="timeline">
      <div class="timeline-item">
        <div class="timeline-marker"></div>
        <div class="timeline-content">
          <div class="timeline-header">
            <h3>Software Engineer Intern</h3>
            <span class="timeline-date">May 2025 - Aug 2025</span>
          </div>
          <p class="timeline-company">Orion Defense Solutions L.L.C. (Remote)</p>
          <ul>
            <li>Built and deployed a Python/FastAPI automation platform integrating LangChain and SQL-backed internal systems, reducing project cycle time by ~8 hours.</li>
            <li>Containerized platform microservices using Docker and Kubernetes, enabling rolling updates and eliminating ~7 hours of manual setup per week.</li>
          </ul>
        </div>
      </div>

      <div class="timeline-item">
        <div class="timeline-marker"></div>
        <div class="timeline-content">
          <div class="timeline-header">
            <h3>Undergraduate Researcher</h3>
            <span class="timeline-date">Jan 2024 - May 2025</span>
          </div>
          <p class="timeline-company">Reality, Autonomy, Robot Experience (RARE) Lab, USF &mdash; Tampa, FL</p>
          <ul>
            <li>Published two first-author papers at ACM/IEEE HRI 2025 (25% acceptance rate) on autonomous fog-screen communication systems.</li>
            <li>Developed ROS nodes in C++ to synchronize Fetch robot behavior, achieving reliable distributed actuation.</li>
          </ul>
        </div>
      </div>
    </div>
  </div>
</section>

<section class="section section-alt" id="projects">
  <div class="container">
    <h2 class="section-title">Projects</h2>

    <div class="card-grid">
      <div class="card">
        <div class="card-tag">HPC</div>
        <h3>High-Performance Parallel Computing</h3>
        <ul>
          <li>Parallelized dense matrix kernels using OpenMP in C++, achieving near-linear <strong>16x speedup</strong> at 16 threads on GT's PACE/ICE cluster.</li>
          <li>Accelerated a heat equation PDE solver on an NVIDIA H100 via CUDA shared memory tiling, achieving up to <strong>83.9x speedup</strong>.</li>
          <li>Implemented MPI-parallel Monte Carlo simulation scaling to 64 processes with <strong>99.7% parallel efficiency</strong>.</li>
          <li>Applied Roofline performance modeling to classify SpMV, stencil, and 3D-FFT kernels on Intel and AMD architectures.</li>
        </ul>
        <div class="card-tags">
          <span>C++</span><span>OpenMP</span><span>CUDA</span><span>MPI</span>
        </div>
      </div>

      <div class="card">
        <div class="card-tag">Robotics</div>
        <h3>Autonomous Ground Vehicle</h3>
        <ul>
          <li>Led a team of 7 to design and build an autonomous vehicle on Raspberry Pi, mentoring peers in Linux development and conducting code reviews.</li>
          <li>Designed and deployed a Flask backend with SQLAlchemy to expose REST endpoints for robot status, logs, and commands.</li>
        </ul>
        <div class="card-tags">
          <span>Python</span><span>Flask</span><span>SQLAlchemy</span><span>Raspberry Pi</span>
        </div>
      </div>

      <div class="card">
        <div class="card-tag">ML</div>
        <h3>GNN-Based Fraud Detection</h3>
        <ul>
          <li>Developed a Graph Neural Network in PyTorch to classify fraudulent financial transactions, achieving <strong>91% accuracy</strong> on real-world datasets.</li>
          <li>Preprocessed graph data with NetworkX, extracting structural features (centrality, clustering coefficients) to improve model performance.</li>
        </ul>
        <div class="card-tags">
          <span>PyTorch</span><span>NetworkX</span><span>Python</span>
        </div>
      </div>
    </div>
  </div>
</section>

<section class="section" id="education">
  <div class="container">
    <h2 class="section-title">Education</h2>

    <div class="edu-grid">
      <div class="edu-item">
        <h3>Georgia Institute of Technology</h3>
        <p class="edu-degree">M.S. Computational Science and Engineering</p>
        <p class="edu-meta">Expected Dec 2026 &bull; GPA: 3.33/4.0</p>
        <p class="edu-detail">Coursework: High Performance Parallel Computing, Numerical Linear Algebra, Modeling and Simulation</p>
      </div>

      <div class="edu-item">
        <h3>University of South Florida</h3>
        <p class="edu-degree">B.S. Computer Engineering, <em>summa cum laude</em></p>
        <p class="edu-meta">Aug 2021 - May 2025 &bull; GPA: 3.9/4.0</p>
        <p class="edu-detail">Honors: FLIT-GAP Scholar, Bright Futures Scholar</p>
        <p class="edu-detail">Coursework: Analysis and Design of Algorithms, Data Structures, Social Networks, Computer Architecture</p>
      </div>
    </div>
  </div>
</section>

<section class="section section-alt" id="skills">
  <div class="container">
    <h2 class="section-title">Skills</h2>

    <div class="skills-grid">
      <div class="skill-group">
        <h4>Languages</h4>
        <div class="skill-tags">
          <span>Python</span><span>C/C++</span><span>SQL</span><span>Bash/Zsh</span><span>JavaScript</span>
        </div>
      </div>
      <div class="skill-group">
        <h4>Parallel / HPC</h4>
        <div class="skill-tags">
          <span>MPI</span><span>OpenMP</span><span>CUDA</span>
        </div>
      </div>
      <div class="skill-group">
        <h4>Tools</h4>
        <div class="skill-tags">
          <span>Git</span><span>Docker</span><span>Kubernetes</span><span>ROS</span>
        </div>
      </div>
      <div class="skill-group">
        <h4>Systems / Areas</h4>
        <div class="skill-tags">
          <span>Data Structures & Algorithms</span><span>Distributed Systems</span><span>HPC</span><span>Unix/Linux</span>
        </div>
      </div>
      <div class="skill-group">
        <h4>Libraries</h4>
        <div class="skill-tags">
          <span>PyTorch</span><span>NumPy</span><span>Pandas</span><span>FastAPI</span><span>Flask</span><span>SQLAlchemy</span><span>LangChain</span><span>NetworkX</span>
        </div>
      </div>
    </div>
  </div>
</section>

<section class="section" id="awards">
  <div class="container">
    <h2 class="section-title">Awards</h2>

    <div class="awards-list">
      <div class="award-item">
        <div class="award-info">
          <h4>UR2PhD Technical Conference Travel Award</h4>
          <p>Computing Research Association (CRA)</p>
        </div>
        <div class="award-meta">
          <span class="award-amount">$2,000</span>
          <span class="award-date">Mar 2025</span>
        </div>
      </div>
      <div class="award-item">
        <div class="award-info">
          <h4>Tampa Conference Presentation Grant Program</h4>
          <p>CPGP</p>
        </div>
        <div class="award-meta">
          <span class="award-amount">$700</span>
          <span class="award-date">Mar 2025</span>
        </div>
      </div>
      <div class="award-item">
        <div class="award-info">
          <h4>NSF Distributed Research Experiences for Undergraduates</h4>
          <p>DREU</p>
        </div>
        <div class="award-meta">
          <span class="award-amount">$7,000</span>
          <span class="award-date">May 2024 - Aug 2024</span>
        </div>
      </div>
      <div class="award-item">
        <div class="award-info">
          <h4>Florida Bright Futures Scholarship</h4>
          <p>100% of Tuition</p>
        </div>
        <div class="award-meta">
          <span class="award-amount">Full Tuition</span>
          <span class="award-date">Aug 2021 - May 2025</span>
        </div>
      </div>
    </div>
  </div>
</section>
