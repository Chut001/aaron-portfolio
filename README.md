<nav>

<a href="#home">Home</a>
<a href="#about">About</a>
<a href="#skills">Skills</a>
<a href="#projects">Projects</a>
<a href="#services">Services</a>
<a href="#contact">Contact</a>

</nav><!-- SERVICES -->

<section id="services">

    <h2>My <span>Services</span></h2>

    <div class="services">

        <div class="service">

            <div class="service-icon">📸</div>

            <h3>Photo Editing</h3>

            <p>
                Professional photo enhancement,
                retouching and creative edits.
            </p>

        </div>


        <div class="service">

            <div class="service-icon">🎨</div>

            <h3>Graphic Design</h3>

            <p>
                Creative flyers, posters,
                birthday designs and social media graphics.
            </p>

        </div>


        <div class="service">

            <div class="service-icon">🌐</div>

            <h3>Website Design</h3>

            <p>
                Modern and responsive websites
                for phones and computers.
            </p>

        </div>


        <div class="service">

            <div class="service-icon">📱</div>

            <h3>Social Media Design</h3>

            <p>
                Attractive designs for social
                media pages and online brands.
            </p>

        </div>

    </div>

</section></style>/* SERVICES */

.services {
    max-width: 900px;
    margin: 30px auto;
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 20px;
}

.service {
    background: #151515;
    padding: 30px 20px;
    border-radius: 20px;
    border: 1px solid #292929;
    transition: 0.3s;
}

.service:hover {
    transform: translateY(-8px);
    border-color: #00d9ff;
}

.service-icon {
    font-size: 40px;
    margin-bottom: 10px;
}

.service h3 {
    color: #00d9ff;
}

@media (max-width: 600px) {

    .services {
        grid-template-columns: 1fr;
    }

}
