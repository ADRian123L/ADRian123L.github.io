---
layout: default
title: Adrian Lozada
---

<section class="hero" id="about" tabindex="-1">
  <div class="container">
    <div class="hero-content">
      <h1>Adrian Lozada</h1>
      <p class="hero-subtitle">M.S. Computational Science &amp; Engineering @ Georgia Tech</p>
      <p class="hero-description">I build high-performance computing systems, parallel algorithms, and intelligent software. My work spans HPC, LLM tooling, distributed systems, robotics, and machine learning.</p>
      <div class="hero-actions">
        <a href="#experience" class="btn btn-primary">See My Work</a>
        <a href="#projects" class="btn btn-outline">View Projects</a>
      </div>
    </div>
  </div>
</section>

<section class="section" id="experience" tabindex="-1">
  <div class="container">
    <h2 class="section-title">Experience</h2>

    <div class="timeline">
      <div class="timeline-item">
        <div class="timeline-marker"></div>
        <div class="timeline-content">
          <div class="timeline-header">
            <h3>Open Source Software Engineer Intern</h3>
            <span class="timeline-date">May 2026 &ndash; Aug 2026</span>
          </div>
          <p class="timeline-company">Center for Scientific Software Engineering (CSSE), Georgia Tech &mdash; Atlanta, GA</p>
          <ul>
            <li>Prototyped an experimental LLM extractor that identifies case-law citations in legal briefs, using Mellea requirements and instruct-validate-repair sampling over backend-agnostic Ollama/LiteLLM endpoints.</li>
            <li>Raised detection recall from 22.2% to <strong>83.3%</strong> and F1 from 34.8 to <strong>85.7</strong> on IBM Granite 4.1 (3&ndash;30B) models, benchmarked against the rule-based eyecite extractor on a frozen citation benchmark.</li>
          </ul>
          <p class="timeline-links">
            <a href="https://github.com/gt-csse/mellea-lrc" target="_blank" rel="noopener noreferrer">
              <svg aria-hidden="true" focusable="false" xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="currentColor"><path d="M12 0c-6.626 0-12 5.373-12 12 0 5.302 3.438 9.8 8.207 11.387.599.111.793-.261.793-.577v-2.234c-3.338.726-4.033-1.416-4.033-1.416-.546-1.387-1.333-1.756-1.333-1.756-1.089-.745.083-.729.083-.729 1.205.084 1.839 1.237 1.839 1.237 1.07 1.834 2.807 1.304 3.492.997.107-.775.418-1.305.762-1.604-2.665-.305-5.467-1.334-5.467-5.931 0-1.311.469-2.381 1.236-3.221-.124-.303-.535-1.524.117-3.176 0 0 1.008-.322 3.301 1.23.957-.266 1.983-.399 3.003-.404 1.02.005 2.047.138 3.006.404 2.291-1.552 3.297-1.23 3.297-1.23.653 1.653.242 2.874.118 3.176.77.84 1.235 1.911 1.235 3.221 0 4.609-2.807 5.624-5.479 5.921.43.372.823 1.102.823 2.222v3.293c0 .319.192.694.801.576 4.765-1.589 8.199-6.086 8.199-11.386 0-6.627-5.373-12-12-12z"/></svg>
              gt-csse/mellea-lrc
            </a>
          </p>
        </div>
      </div>

      <div class="timeline-item">
        <div class="timeline-marker"></div>
        <div class="timeline-content">
          <div class="timeline-header">
            <h3>Software Engineer Intern</h3>
            <span class="timeline-date">May 2025 &ndash; Aug 2025</span>
          </div>
          <p class="timeline-company">Orion Defense Solutions L.L.C. &mdash; Remote</p>
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
            <span class="timeline-date">Jan 2024 &ndash; May 2025</span>
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

<section class="section section-alt" id="projects" tabindex="-1">
  <div class="container">
    <h2 class="section-title">Projects</h2>

    <div class="card-grid">
      <div class="card">
        <div class="card-tag">HPC</div>
        <h3>High-Performance Parallel Computing</h3>
        <ul>
          <li>Parallelized dense matrix kernels using OpenMP work-sharing and loop-collapse strategies in C++, achieving near-linear <strong>16x speedup</strong> at 16 threads on GT's PACE/ICE cluster.</li>
          <li>Accelerated a heat equation PDE solver on an NVIDIA H100 via CUDA shared memory tiling and OpenMP GPU offloading, achieving up to <strong>83.9x</strong> and <strong>17x</strong> speedup respectively over single-threaded CPU baselines.</li>
        </ul>
        <div class="card-tags">
          <span>C++</span><span>OpenMP</span><span>CUDA</span>
        </div>
      </div>

      <div class="card">
        <div class="card-tag">ML</div>
        <h3>Graph Neural Network-Based Fraud Detection</h3>
        <ul>
          <li>Developed a Graph Neural Network in PyTorch to classify fraudulent financial transactions, achieving <strong>91% F1 score</strong> on real-world datasets.</li>
        </ul>
        <div class="card-tags">
          <span>PyTorch</span><span>NetworkX</span><span>Python</span>
        </div>
      </div>

      <div class="card">
        <div class="card-tag">Robotics</div>
        <h3>Autonomous Ground Vehicle with Remote Monitoring System</h3>
        <ul>
          <li>Led a team of 7 to design and build an autonomous vehicle on Raspberry Pi, mentoring peers in Linux development and conducting code reviews to deliver a working prototype.</li>
          <li>Designed and deployed a Flask backend with SQLAlchemy to expose REST endpoints for robot status, logs, and commands.</li>
        </ul>
        <div class="card-tags">
          <span>Python</span><span>Flask</span><span>SQLAlchemy</span><span>Raspberry Pi</span>
        </div>
      </div>
    </div>
  </div>
</section>

<section class="section" id="education" tabindex="-1">
  <div class="container">
    <h2 class="section-title">Education</h2>

    <div class="edu-grid">
      <div class="edu-item">
        <h3>Georgia Institute of Technology</h3>
        <p class="edu-degree">M.S. Computational Science and Engineering</p>
        <p class="edu-meta">Expected Dec 2026 &bull; Atlanta, GA &bull; GPA: 3.5/4.0</p>
        <p class="edu-detail">Coursework: High Performance Parallel Computing, Numerical Linear Algebra, Modeling and Simulation</p>
      </div>

      <div class="edu-item">
        <h3>University of South Florida</h3>
        <p class="edu-degree">B.S. Computer Engineering, <em>summa cum laude</em></p>
        <p class="edu-meta">Aug 2021 &ndash; May 2025 &bull; Tampa, FL &bull; GPA: 3.9/4.0</p>
        <p class="edu-detail">Honors: FLIT-GAP Scholar, Bright Futures Scholar</p>
        <p class="edu-detail">Coursework: Analysis and Design of Algorithms, Data Structures, Social Networks, Computer Architecture</p>
      </div>
    </div>
  </div>
</section>

<section class="section section-alt" id="skills" tabindex="-1">
  <div class="container">
    <h2 class="section-title">Skills</h2>

    <div class="skills-grid">
      <div class="skill-group">
        <h3>Languages</h3>
        <div class="skill-tags">
          <span>Python</span><span>C/C++</span><span>SQL</span><span>Bash/Zsh</span>
        </div>
      </div>
      <div class="skill-group">
        <h3>Parallel / HPC</h3>
        <div class="skill-tags">
          <span>MPI</span><span>OpenMP</span><span>CUDA</span><span>Slurm</span>
        </div>
      </div>
      <div class="skill-group">
        <h3>Tools</h3>
        <div class="skill-tags">
          <span>Git</span><span>Docker</span><span>Kubernetes</span><span>ROS</span>
        </div>
      </div>
      <div class="skill-group">
        <h3>Libraries</h3>
        <div class="skill-tags">
          <span>PyTorch</span><span>NumPy</span><span>Pandas</span><span>FastAPI</span><span>Flask</span><span>SQLAlchemy</span><span>LangChain</span><span>NetworkX</span>
        </div>
      </div>
    </div>
  </div>
</section>

<section class="section" id="awards" tabindex="-1">
  <div class="container">
    <h2 class="section-title">Awards</h2>

    <div class="awards-list">
      <div class="award-item">
        <div class="award-info">
          <h3>UR2PhD Technical Conference Travel Award</h3>
          <p>Computing Research Association (CRA)</p>
        </div>
        <div class="award-meta">
          <span class="award-amount">$2,000</span>
          <span class="award-date">Mar 2025</span>
        </div>
      </div>
      <div class="award-item">
        <div class="award-info">
          <h3>Tampa Conference Presentation Grant Program</h3>
          <p>CPGP</p>
        </div>
        <div class="award-meta">
          <span class="award-amount">$700</span>
          <span class="award-date">Mar 2025</span>
        </div>
      </div>
      <div class="award-item">
        <div class="award-info">
          <h3>NSF Distributed Research Experiences for Undergraduates</h3>
          <p>DREU</p>
        </div>
        <div class="award-meta">
          <span class="award-amount">$7,000</span>
          <span class="award-date">May 2024 &ndash; Aug 2024</span>
        </div>
      </div>
      <div class="award-item">
        <div class="award-info">
          <h3>Florida Bright Futures Scholarship</h3>
          <p>100% of Tuition</p>
        </div>
        <div class="award-meta">
          <span class="award-amount">Full Tuition</span>
          <span class="award-date">Aug 2021 &ndash; May 2025</span>
        </div>
      </div>
    </div>
  </div>
</section>
