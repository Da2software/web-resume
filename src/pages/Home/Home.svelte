<script>
    import Progressbar from "../../components/Progressbar.svelte";
    let skillIcons = [
        {
            id: "python",
            path: "assets/icons/python.svg",
            value: 85,
            name: "python",
        },
        { id: "angular", path: "assets/icons/angular.svg", value: 85 },
        { id: "vuejs", path: "assets/icons/vuejs.svg", value: 50 },
        { id: "svelte", path: "assets/icons/svelte.svg", value: 50 },
        { id: "react", path: "assets/icons/react.svg", value: 35 },
        { id: "nodejs/js", path: "assets/icons/nodejs02.svg", value: 75 },
        { id: "django", path: "assets/icons/django.svg", value: 70 },
        { id: "sql", path: "assets/icons/sql-file-format.svg", value: 65 },
        { id: "mongodb", path: "assets/icons/mongodb.svg", value: 60 },
        {
            id: "elasticsearch",
            path: "assets/icons/elasticsearch.svg",
            value: 70,
        },
        { id: "html5", path: "assets/icons/html5-01.svg", value: 80 },
        { id: "css", path: "assets/icons/css3-01.svg", value: 72 },
    ];
</script>

<main>
    <div class="row justify-content-center profile-bg" id="home">
        <div class="col-sm-12 pad-bg align-self-center h-100">
            <div class="row m-auto">
                <div class="row justify-content-center align-self-center">
                    <div class="col-md-8 col-sm-12 row text-center">
                        <h2
                            class="animate__animated animate__backInLeft animate__delay-0-2s"
                        >
                            Hello I'm
                        </h2>
                        <h1
                            class="animate__animated animate__backInRight animate__delay-0-3s"
                        >
                            Pedro Uh
                        </h1>
                        <h4
                            class="animate__animated animate__backInDown animate__delay-0-4s"
                        >
                            Advance Full Stack Devaloper
                        </h4>
                    </div>
                </div>
                <div
                    class="row justify-content-center align-self-center social-m mt-4"
                >
                    <div class="col-sm-6 pt-2">
                        <div
                            class="row justify-content-center icons animate__animated animate__slideInRight"
                        >
                            <a
                                href="http://linkedin.com/in/pedro-gildardo-uh-ihuit-a01825168"
                                target="_blank"
                            >
                                <i
                                    class="bi bi-linkedin animate__animated animate__fadeIn animate__delay-0-8s"
                                />
                            </a>
                            <a
                                href="http://www.instagram.com/dados_07/"
                                target="_blank"
                            >
                                <i
                                    class="bi bi-instagram animate__animated animate__fadeIn animate__delay-0-9s"
                                />
                            </a>
                            <a
                                href="https://github.com/Da2software"
                                target="_blank"
                            >
                                <i
                                    class="bi bi-github animate__animated animate__fadeIn animate__delay-1s"
                                />
                            </a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <!-- ABOUT ME -->
    <div
        class="row justify-content-center align-self-center"
        id="about-me-site"
    >
        <div class="col-sm-12 col-md-6">
            <div class="section-box row justify-content-center">
                <div class="col-sm-4 flex">
                    <img
                        src="assets/img/profile4k.jpg"
                        alt="profile"
                        class="profile-img"
                    />
                </div>
                <div class="col-sm-8 grid">
                    <h1 class="title">About me</h1>
                    <p>
                        I am an experienced full-stack developer with a
                        background in SQL and No-SQL databases. With over five
                        years of experience. I have worked on various projects,
                        from startups to large-scale clients. I have a solid
                        understanding of the MEAN stack, Postgresql, Nodejs,
                        Angular, Flask, Django, and Vuejs. I have also worked on
                        projects involving web system development, scientific
                        document analytics, and psychometric analysis.
                    </p>
                    <p>
                        I am a self-learner who likes to share knowledge. I am
                        passionate about learning new technologies and working
                        with different stacks. I am interested in learning more
                        about Vuejs, Svelte, No-SQL databases, and Machine
                        Learning or AI. I am a quick learner and adapt quickly
                        to new environments.
                    </p>
                    <p>oh, and I love cats and drawing in my free time :)</p>
                    <div class="row">
                        <div class="col-12" />
                    </div>
                </div>
            </div>
        </div>
    </div>
    <!-- EDUCATION -->
    <div
        class="row justify-content-center align-self-center white-bg"
        id="education"
    >
        <div class="col-sm-12 col-md-6 bd-b">
            <div class="section-box row justify-content-center">
                <div class="col-sm-4">
                    <h2 class="title-dark">Education</h2>
                </div>
                <div class="col-sm-8">
                    <h1 class="title-second">Computer Systems Engineer</h1>
                    <span class="label-second my-1"><b>2015 - 2018</b></span>
                    <h4 class="subtitle-second">
                        ITSSY(Instituto Superior del Sur del estado de Yucatán)
                    </h4>
                </div>
            </div>
        </div>
    </div>
    <!-- WORK -->
    <div
        class="row justify-content-center align-self-center white-bg"
        id="work-exp"
    >
        <div class="col-sm-12 col-md-6 bd-b">
            <div class="section-box row justify-content-center">
                <div class="col-sm-4">
                    <h2 class="title-dark">Work Experience</h2>
                </div>
                <div class="col-sm-8">
                    <h1 class="title-second">Software Hose Merida</h1>
                    <span class="label-second my-1"
                        ><b>2018 - currently working here</b></span
                    >
                    <h4 class="subtitle-second mt-2"><b>Internship</b></h4>
                    <p class="dark mt-1">
                        During my internship, I worked on a startup that focused
                        on risk case analysis for lawyers and I worked on SQL
                        optimization and automation to improve the system's
                        performance.
                    </p>
                    <h4 class="subtitle-second mt-2">
                        <b>Jr. Full Stack Developer</b>
                    </h4>
                    <p class="dark mt-1">
                        I worked for a startup about a web system to help
                        patients find therapists. I built the project from
                        scratch, including microservices architecture using
                        Postgresql, Nodejs with Express and Angular, also, I
                        deployed the project using AWS. I collaborated with
                        another startup for advanced searching and analytics of
                        scientific documents. I used Python to automate the
                        porting of documentation from PubMed API and used the
                        MEAN stack to create the web system page.
                    </p>
                    <p class="dark mt-1">
                        I worked in another startup about a web system to help
                        patients find therapists. I built the project from
                        scratch, including microservices architecture using
                        Postgresql, Nodejs with Express and Angular, also, I
                        deployed the project using AWS. I collaborated with
                        another startup for advanced searching and analytics of
                        scientific documents. I used Python to automate the
                        porting of documentation from PubMed API and used the
                        MEAN stack to create the web system page.
                    </p>
                    <h4 class="subtitle-second mt-2">
                        <b>Intermediate to Advanced Full Stack Developer </b>
                    </h4>
                    <p class="dark mt-1">
                        Currently working for a client that specializes in
                        psychometric analysis information. I am responsible for
                        optimizing, creating Angular frameworks, and porting
                        projects to different technologies. I am working with
                        different stacks such as Elastic Search, Python with
                        Flask, Angular, Microsoft SQL Server with Python, and
                        Django.
                    </p>
                </div>
            </div>
        </div>
    </div>
    <!-- SKILL -->
    <div
        class="row justify-content-center align-self-center white-bg"
        id="skills"
    >
        <div class="col-sm-12 col-md-6 bd-b">
            <div class="section-box row justify-content-center">
                <div class="col-sm-4">
                    <h2 class="title-dark">Skills</h2>
                </div>
                <div class="col-sm-8">
                    {#each skillIcons as skill}
                        <div class="row mb-4" id={skill.path + "-icon"}>
                            <div class="col-12">
                                <h3 class="icon-title">{skill.id}</h3>
                            </div>
                            <div class="col-sm-2 row">
                                <img
                                    title={skill.id}
                                    class="icon m-auto col"
                                    src={skill.path}
                                    alt={skill.id}
                                />
                            </div>
                            <div class="col-sm-10 row">
                                <div
                                    class="h-fit-content col-12 align-self-center"
                                >
                                    <Progressbar
                                        class="my-auto"
                                        progress={skill.value}
                                    />
                                </div>
                            </div>
                        </div>
                    {/each}
                </div>
            </div>
        </div>
    </div>
    <!-- CONTACT -->
    <div
        class="row justify-content-center align-self-center white-bg"
        id="contact"
    >
        <div class="col-sm-12 col-md-6 bd-b">
            <div class="section-box row justify-content-center">
                <div class="col-sm-4">
                    <h2 class="title-dark">Contact me</h2>
                </div>
                <div class="col-sm-8" />
            </div>
        </div>
    </div>
</main>

<style>
    .white-bg {
        background-color: aliceblue;
    }
    .bd-b {
        border-bottom: 2px solid var(--primary-border);
    }
    .profile-bg {
        height: 100%;
        width: 100%;
        overflow-y: hidden;
        background-image: url("/assets/img/bg-ai-dev.jpeg");
        background-attachment: fixed;
        background-position: center;
        background-repeat: no-repeat;
        background-size: cover;
        height: 100vh;
    }
    .profile-bg .pad-bg {
        display: flex;
        padding-top: 10rem;
        padding-bottom: 10rem;
        background-color: #00000070;
    }
    .profile-img {
        margin: auto;
        width: 80%;
        height: auto;
        border-radius: 50%;
        border: 2px solid var(--background-hover);
    }
    .section-box {
        margin: 5rem 0;
        height: fit-content;
        min-height: 100px;
    }
    .section-box .title {
        font-size: 32px;
        color: var(--primary-text);
    }
    .social-m .icons {
        border-top: 1px solid #ffffffad;
        padding-top: 1rem;
    }
    .social-m .icons .bi {
        color: var(--primary-text);
        font-size: 2rem;
        width: fit-content;
        margin: 0 1rem;
    }
    .social-m .icons a {
        width: fit-content;
    }
    .icon {
        width: 3rem;
        height: auto;
    }
    .icon-title {
        text-align: center;
        font-size: 1.2rem;
        display: inline-block;
        margin-bottom: 0.3rem;
        text-transform: capitalize;
        color: var(--primary-border);
    }
</style>
