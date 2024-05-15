<script>
  import Section from "./Section.svelte";
  import Work from "./Work.svelte";
</script>

<main class="w-100">
  <div class="page-container">
    <div class="title">
      <h1 id="name" class="my-2">Pedro Uh</h1>
    </div>
    <div class="info-desc">
      <h6 id="info">
        <!-- 97840, Yucatan México | 9992056369 | pedro.gil.uh@gmail.com -->
        Yucatan México | 9992056369 | pedro.gil.uh@gmail.com 
      </h6>
    </div>
    <Section title={"Professional Summary"}>
      <p class="mx-2 my-4">
        I bring over five years of extensive experience in software development,
        specializing in different back-end technologies and building
        applications architectures from scratch. My proficiency spans both SQL
        and No-SQL databases, I worked directly with US-based clients, and I
        collaborated with cross-functional teams in an Agile environment. I’m a
        self-learner and l really enjoy sharing knowledge with others.
      </p>
    </Section>

    <Section title={"Skills"}>
      <div class="mx-2 my-4 row" id="skills">
        <div class="col-6">
          <li>
            Python, Nodejs, TypeScript, JavaScript, HTML, Css, Scss, Golang
          </li>
          <li>
            Django, Express, FastApi, Flask, Vuejs, Angular, Svelte, React, Ruby
            and rails, Tensorflow
          </li>
        </div>
        <div class="col-6">
          <li>MongoDB, SQL, Sqlserver, Postgresql, Elasticsearch</li>
          <li>
            Docker, Jira, Microservices architecture, Shell / Bash scripting,
            Software Best Practices, Teamwork and Collaboration
          </li>
        </div>
      </div>
    </Section>
    <Section title={"Work History"}>
      <Work
        Role={"Full Stack Developer"}
        Company={"Software House Mérida"}
        StarDate={"06/2018"}
        EndDate={"Current"}
      >
        <p>
          <i class="sub-role">Internship Developer:</i>
          <li>
            Designed and implemented an SQL optimization and automation script,
            enhancing database performance and readability.
          </li>
          <li>
            I worked on UI changes for a project about prediction and assistance
            software for lawyers.
          </li>
          <i class="sub-role">Junior Full Stack Developer:</i>
          <li>
            I developed the entire application architecture project for a third
            US-based client, for a mental health related web application using
            MongoDB, Express, Node.js, Angular (MEAN), PostgreSQL, and Python,
            and also I created an the main algorithm for the application.
          </li>
          <li>
            Designed and implemented an entire PostgreSQL database architecture.
          </li>
          <li>
            Built main features for two projects at the same time on the back
            end (Node.js) and front-end (Angular) side, and also successfully
            deployed both projects to AWS environments.
          </li>
          <li>
            Developed advanced Python scripts for porting data from a PubMed API
            to our application.
          </li>
          <i class="sub-role">Intermediate to Advanced Full Stack Developer:</i>
          <li>
            I worked on software architectures over microservices and building
            framework libraries for Angular, also working on Python as a backend
            with Elasticsearch and SQL as a database.
          </li>
          <li>
            Provided comprehensive technical training to new and existing
            DevOps, Developers, QA, and QA automation team members.
          </li>
          <li>
            Improved a key feature for generating back-end (Python) and
            front-end (Angular) reports, aiding in achieving delivery times.
          </li>
          <li>
            Developed an advanced custom UI editor (Angular) and built a complex
            dynamic data handler on the back-end (Python) to be rendered on the
            front end, facilitating dynamic content creation for clients.
          </li>
          <li>
            Developed a pipeline system using Python and Jenkins for
            transforming data asynchronously, optimizing response times, and
            data visualization.
          </li>
          <li>
            Designed analysis to implement robust unit testing frameworks, and
            created testing showcases and demos for client comprehension.
          </li>
          <li>
            Developed an Elasticsearch node architecture analysis report to
            provide actionable insights for DevOps optimization and risk
            mitigation Facilitated a DevOps team in the CI/CD process and
            troubleshooting environment server issues.
          </li>
          <li>
            Ported a project stack from Python, Flask, Elasticsearch, and
            Angular to Python, Django, SQL server, and Angular. Built a
            microservice API from scratch using Python and Django to provide
            necessary information to the front-end application.
          </li>
          <li>
            Contributed to feature development, screen design, and custom
            component creation using Vue.js.
          </li>
        </p>
      </Work>
      <Work
        Role={"Full Stack Developer"}
        Company={"Freelance"}
        StarDate={"09/2023"}
        EndDate={"11/2023"}
      >
        <p>
          <li>
            Developed back-end and front-end for a web system to analyze product
            sales using Python with Flask, PostgreSQL and React.
          </li>
          <li>
            Developed key features to generate PDF reports using Python and
            create front-end graphs using Vue.js, enhanced project architecture,
            and implemented code standards.
          </li>
        </p>
      </Work>
      <Work
        Role={"Full Stack Developer"}
        Company={"Freelance"}
        StarDate={"04/2021"}
        EndDate={"09/2022"}
      >
        <p>
          <li>
            Developed a task scheduling system for product visualization and
            home installation of air conditioners using Vue.js.
          </li>
          <li>
            Managed endpoint maintenance for the back-end (Python with Django),
            ensuring optimal functionality and performance.
          </li>
        </p>
      </Work>
      <Work Role={"Professional Achievements,"}>
        <p>
          <li>
            I built a python game titled “space-invaders-like” as a personal
            challenge to learn how to use pygame.
          </li>
          <li>
            I created a personal project with machine learning to restore an
            historical picture from low quality to a high quality image. This
            project was made using primarily Tensorflow, CUDA and AI for
            denoising image created by me, along with a Microsoft AI project to
            restore old photos.
          </li>
          <li>
            I gave a MEAN stack conference at Software House Mérida (2019).
          </li>
          <li>
            I gave a conference about “Using Python and Raspberry pi to
            monitoring stevia growth” at “Instituto Tecnológico Superior del Sur
            del Estado de Yucatán” (ITSSY) (2019).
          </li>
        </p>
      </Work>
    </Section>

    <div class="w-100 row mt-3">
      <div class="col-6">
        <Section title={"Education"}>
          <div class="mt-4">
            <span class="mt-5 mb-2"
              ><strong>Computer Systems Engineer: </strong>2018</span
            > <br />
            <span><strong>ITSSY</strong> - Oxkutzcab, Yucatán, México.</span>
          </div>
        </Section>
      </div>
      <div class="col-6">
        <Section title={"Languages"}>
          <div class="mt-4">
            <span class="mt-4 mb-2"><strong>English</strong></span> <br />
            Upper intermediate
          </div>
        </Section>
      </div>
    </div>
  </div>
</main>

<style>
  .page-container {
    display: flex;
    flex-direction: column;
    width: 100vw;
  }
  .title {
    display: flex;
    width: 100%;
    border-bottom: solid black 2px;
  }
  .title h1 {
    width: fit-content;
    margin: 1rem auto;
  }
  .info-desc {
    display: flex;
    width: 100%;
  }
  .info-desc h6 {
    font-size: .9rem;
    color: #616161;
    width: fit-content;
    margin: 0.5rem auto;
  }
  .sub-role {
    color: #424242;
    font-weight: bolder;
    width: 100%;
    display: inline-block;
    margin-top: 0.7rem;
    margin-bottom: 0.2rem;
  }
</style>
