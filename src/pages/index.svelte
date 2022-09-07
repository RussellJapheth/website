<script>
    import { metatags } from "@roxi/routify";

    metatags.title = "Russell's portfolio";
    metatags.description = "Lorem ipsum sit dolor amit. I build stuff too";

    /**
     * @type {number}
     */
    let currentYear = new Date().getFullYear();
</script>

<main>
    <section class="w3l-bootstrap-header">
        <nav class="navbar navbar-expand-lg navbar-light py-lg-3 py-2">
            <div class="container">
                <a class="navbar-brand" href="/"> My Website</a>
            </div>
        </nav>
    </section>
    <!--  Main banner section -->
    <section class="w3l-main-banner" id="home">
        <div class="companies20-content">
            <div class="companies-wrapper">
                <div class="item">
                    <div class="slider-info banner-view text-center">
                        <div class="banner-info container">
                            <img
                                src="assets/images/c1.jpg"
                                class="img-fluid"
                                alt="Russell"
                            />
                            <h3 class="banner-text mt-5">
                                Hello, I’m Mark Waugh
                            </h3>
                            <p class="my-4 mb-5">Photographer</p>
                            <br />
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!--  //Main banner section -->
    <section class="w3l-about ">
        <div class="skills-bars py-5">
            <div class="container py-md-3">
                <div class="heading text-center mx-auto">
                    <h3 class="head">Welcome To My Site</h3>
                    <p class="my-3 head">
                        Vestibulum ante ipsum primis in faucibus orci luctus et
                        ultrices posuere cubilia Curae; Nulla mollis dapibus
                        nunc, ut rhoncus turpis sodales quis. Integer sit amet
                        mattis quam.Vestibulum ante ipsum primis in faucibus
                        orci luctus et ultrices posuere cubilia Curae; Nulla
                        mollis dapibus nunc
                    </p>
                </div>
                <div class="row mt-5 pt-3">
                    <div
                        class="col-lg-4 col-md-4 col-sm-6 skills-bar-grids mb-4 pb-2"
                    >
                        <h4>Design</h4>
                        <div class="progress">
                            <div
                                class="progress-bar progress-bar-striped bg-color"
                                role="progressbar"
                                style="width: 50% ;height:4px;"
                                aria-valuenow="50"
                                aria-valuemin="0"
                                aria-valuemax="100"
                            />
                        </div>
                    </div>
                    <div
                        class="col-lg-4 col-md-4 col-sm-6 skills-bar-grids mb-4 pb-2"
                    >
                        <h4>Marketing</h4>
                        <div class="progress">
                            <div
                                class="progress-bar progress-bar-striped bg-color"
                                role="progressbar"
                                style="width: 80% ;height:4px;"
                                aria-valuenow="50"
                                aria-valuemin="0"
                                aria-valuemax="100"
                            />
                        </div>
                    </div>
                    <div
                        class="col-lg-4  col-md-4 col-sm-6 skills-bar-grids mb-4 pb-2"
                    >
                        <h4>Photography</h4>
                        <div class="progress">
                            <div
                                class="progress-bar progress-bar-striped bg-color"
                                role="progressbar"
                                style="width: 60% ;height:4px;"
                                aria-valuenow="50"
                                aria-valuemin="0"
                                aria-valuemax="100"
                            />
                        </div>
                    </div>
                    <div
                        class="col-lg-4  col-md-4 col-sm-6 skills-bar-grids mb-4 pb-2"
                    >
                        <h4>Branding</h4>
                        <div class="progress">
                            <div
                                class="progress-bar progress-bar-striped bg-color"
                                role="progressbar"
                                style="width: 70% ;height:4px;"
                                aria-valuenow="50"
                                aria-valuemin="0"
                                aria-valuemax="100"
                            />
                        </div>
                    </div>
                    <div
                        class="col-lg-4  col-md-4 col-sm-6 skills-bar-grids mb-4 pb-2"
                    >
                        <h4>Development</h4>
                        <div class="progress">
                            <div
                                class="progress-bar progress-bar-striped bg-color"
                                role="progressbar"
                                style="width: 90% ;height:4px;"
                                aria-valuenow="50"
                                aria-valuemin="0"
                                aria-valuemax="100"
                            />
                        </div>
                    </div>
                    <div class="col-lg-4 col-md-4 col-sm-6 skills-bar-grids ">
                        <h4>SEO</h4>
                        <div class="progress">
                            <div
                                class="progress-bar progress-bar-striped bg-color"
                                role="progressbar"
                                style="width: 80% ;height:4px;"
                                aria-valuenow="50"
                                aria-valuemin="0"
                                aria-valuemax="100"
                            />
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <section class="w3l-features-4">
        <!-- /features -->
        <div class="features py-5" id="services">
            <div class="container py-md-3">
                <div class="heading text-center mx-auto">
                    <h3 class="head">My Services</h3>
                    <p class="my-3 head">
                        Vestibulum ante ipsum primis in faucibus orci luctus et
                        ultrices posuere cubilia Curae; Nulla mollis dapibus
                        nunc, ut rhoncus turpis sodales quis. Integer sit amet
                        mattis quam.
                    </p>
                </div>
                <div class="fea-gd-vv row mt-5 pt-3">
                    <div class="float-lt feature-gd col-lg-4 col-md-6">
                        <div class="icon">
                            <span class="fa fa-code" aria-hidden="true" />
                        </div>
                        <div class="icon-info">
                            <h5><a href="#"> Website Design</a></h5>
                            <p>
                                Lorem ipsum dolor sit amet, consectetur
                                adipisicingelit, sed do eiusmod tempor
                                incididunt
                            </p>
                            <a href="#" class="red mt-3"
                                >Read More <span
                                    class="fa fa-angle-right pl-1"
                                /></a
                            >
                        </div>
                    </div>
                    <div
                        class="float-mid feature-gd col-lg-4 col-md-6 mt-md-0 mt-5"
                    >
                        <div class="icon">
                            <span class="fa fa-cogs" aria-hidden="true" />
                        </div>
                        <div class="icon-info">
                            <h5><a href="#">Web Development </a></h5>
                            <p>
                                Lorem ipsum dolor sit amet, consectetur
                                adipisicingelit, sed do eiusmod tempor
                                incididunt
                            </p>
                            <a href="#" class="red mt-3"
                                >Read More <span
                                    class="fa fa-angle-right pl-1"
                                /></a
                            >
                        </div>
                    </div>
                    <div
                        class="float-rt feature-gd col-lg-4 col-md-6 mt-lg-0 mt-5"
                    >
                        <div class="icon">
                            <span class="fa fa-mobile" aria-hidden="true" />
                        </div>
                        <div class="icon-info">
                            <h5><a href="#">App Development</a></h5>
                            <p>
                                Lorem ipsum dolor sit amet, consectetur
                                adipisicingelit, sed do eiusmod tempor
                                incididunt
                            </p>
                            <a href="#" class="red mt-3"
                                >Read More <span
                                    class="fa fa-angle-right pl-1"
                                /></a
                            >
                        </div>
                    </div>
                    <div class="float-lt feature-gd col-lg-4 col-md-6 mt-5">
                        <div class="icon">
                            <span class="fa fa-lock" aria-hidden="true" />
                        </div>
                        <div class="icon-info">
                            <h5><a href="#">Cyber Security</a></h5>
                            <p>
                                Lorem ipsum dolor sit amet, consectetur
                                adipisicingelit, sed do eiusmod tempor
                                incididunt
                            </p>
                            <a href="#" class="red mt-3"
                                >Read More <span
                                    class="fa fa-angle-right pl-1"
                                /></a
                            >
                        </div>
                    </div>
                    <div class="float-mid feature-gd col-lg-4 col-md-6 mt-5">
                        <div class="icon">
                            <span class="fa fa-bar-chart" aria-hidden="true" />
                        </div>
                        <div class="icon-info">
                            <h5><a href="#"> Digital Marketing</a></h5>
                            <p>
                                Lorem ipsum dolor sit amet, consectetur
                                adipisicingelit, sed do eiusmod tempor
                                incididunt
                            </p>
                            <a href="#" class="red mt-3"
                                >Read More <span
                                    class="fa fa-angle-right pl-1"
                                /></a
                            >
                        </div>
                    </div>
                    <div class="float-rt feature-gd col-lg-4 col-md-6 mt-5">
                        <div class="icon">
                            <span class="fa fa-info" aria-hidden="true" />
                        </div>
                        <div class="icon-info">
                            <h5><a href="#">Other Catagory</a></h5>
                            <p>
                                Lorem ipsum dolor sit amet, consectetur
                                adipisicingelit, sed do eiusmod tempor
                                incididunt
                            </p>
                            <a href="#" class="red mt-3"
                                >Read More <span
                                    class="fa fa-angle-right pl-1"
                                /></a
                            >
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <!-- //features -->
    </section>
    <section class="w3l-feature-3" id="features">
        <div class="grid top-bottom">
            <div class="container">
                <div class="heading text-center mx-auto">
                    <h3 class="head text-white">I'm Available For Hire</h3>
                    <p class="my-3 head text-white">
                        Vestibulum ante ipsum primis in faucibus orci luctus et
                        ultrices posuere cubilia Curae; Nulla mollis dapibus
                        nunc, ut rhoncus turpis sodales quis. Integer sit amet
                        mattis quam.
                    </p>
                </div>
                <div class="middle-section grid-column text-center mt-5 pt-3">
                    <div class="three-grids-columns">
                        <span class="fa fa-paint-brush" />
                        <h4>Design</h4>
                        <p>
                            Vestibulum ante ipsum primis in faucibus orci luctus
                            et ultrices posuere cubilia Curae; Nulla mollis
                            dapibus nunc
                        </p>
                    </div>
                    <div class="three-grids-columns">
                        <span class="fa fa-ils" />
                        <h4>Marketing</h4>
                        <p>
                            Vestibulum ante ipsum primis in faucibus orci luctus
                            et ultrices posuere cubilia Curae; Nulla mollis
                            dapibus nunc
                        </p>
                    </div>
                    <div class="three-grids-columns">
                        <span class="fa fa-camera" />
                        <h4>Photography</h4>
                        <p>
                            Vestibulum ante ipsum primis in faucibus orci luctus
                            et ultrices posuere cubilia Curae; Nulla mollis
                            dapibus nunc
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <div class="products-4" id="portfolio">
        <!-- Products4 block -->
        <div id="products4-block" class="text-center">
            <div class="container">
                <div class="heading text-center mx-auto mb-5">
                    <h3 class="head">I Love What I Do</h3>
                    <p class="my-3 head">
                        Vestibulum ante ipsum primis in faucibus orci luctus et
                        ultrices posuere cubilia Curae; Nulla mollis dapibus
                        nunc, ut rhoncus turpis sodales quis. Integer sit amet
                        mattis quam.
                    </p>
                </div>
                <input id="tab1" type="radio" name="tabs" checked />
                <label class="tabtle" for="tab1">All Projects</label>

                <input id="tab2" type="radio" name="tabs" />
                <label class="tabtle" for="tab2">Illustration</label>

                <input id="tab3" type="radio" name="tabs" />
                <label class="tabtle" for="tab3">Photography</label>

                <input id="tab4" type="radio" name="tabs" />
                <label class="tabtle" for="tab4">Website</label>

                <section id="content1" class="tab-content text-left">
                    <div class="d-grid grid-col-3">
                        <div class="product">
                            <a
                                href="assets/images/g1.jpg"
                                data-lightbox="example-set"
                                data-title="Lorem ipsum dolor sit amet consectetur adipisicing elit. Numquam architecto, ex veritatis"
                            >
                                <figure>
                                    <img
                                        src="assets/images/g1.jpg"
                                        class="img-responsive"
                                        alt=""
                                    />
                                </figure>
                            </a>
                        </div>
                        <div class="product">
                            <a
                                href="assets/images/g2.jpg"
                                data-lightbox="example-set"
                                data-title="Lorem ipsum dolor sit amet consectetur adipisicing elit. Numquam architecto, ex veritatis"
                            >
                                <figure>
                                    <img
                                        src="assets/images/g2.jpg"
                                        class="img-responsive"
                                        alt=""
                                    />
                                </figure>
                            </a>
                        </div>
                        <div class="product">
                            <a
                                href="assets/images/g3.jpg"
                                data-lightbox="example-set"
                                data-title="Lorem ipsum dolor sit amet consectetur adipisicing elit. Numquam architecto, ex veritatis"
                            >
                                <figure>
                                    <img
                                        src="assets/images/g3.jpg"
                                        class="img-responsive"
                                        alt=""
                                    />
                                </figure>
                            </a>
                        </div>
                        <div class="product">
                            <a
                                href="assets/images/g4.jpg"
                                data-lightbox="example-set"
                                data-title="Lorem ipsum dolor sit amet consectetur adipisicing elit. Numquam architecto, ex veritatis"
                            >
                                <figure>
                                    <img
                                        src="assets/images/g4.jpg"
                                        class="img-responsive"
                                        alt=""
                                    />
                                </figure>
                            </a>
                        </div>
                        <div class="product">
                            <a
                                href="assets/images/g5.jpg"
                                data-lightbox="example-set"
                                data-title="Lorem ipsum dolor sit amet consectetur adipisicing elit. Numquam architecto, ex veritatis"
                            >
                                <figure>
                                    <img
                                        src="assets/images/g5.jpg"
                                        class="img-responsive"
                                        alt=""
                                    />
                                </figure>
                            </a>
                        </div>
                        <div class="product">
                            <a
                                href="assets/images/g6.jpg"
                                data-lightbox="example-set"
                                data-title="Lorem ipsum dolor sit amet consectetur adipisicing elit. Numquam architecto, ex veritatis"
                            >
                                <figure>
                                    <img
                                        src="assets/images/g6.jpg"
                                        class="img-responsive"
                                        alt=""
                                    />
                                </figure>
                            </a>
                        </div>
                    </div>
                </section>

                <section id="content2" class="tab-content text-left">
                    <div class="d-grid grid-col-3">
                        <div class="product">
                            <a
                                href="assets/images/g7.jpg"
                                data-lightbox="example-set"
                                data-title="Lorem ipsum dolor sit amet consectetur adipisicing elit. Numquam architecto, ex veritatis"
                            >
                                <figure>
                                    <img
                                        src="assets/images/g7.jpg"
                                        class="img-responsive"
                                        alt=""
                                    />
                                </figure>
                            </a>
                        </div>
                        <div class="product">
                            <a
                                href="assets/images/g8.jpg"
                                data-lightbox="example-set"
                                data-title="Lorem ipsum dolor sit amet consectetur adipisicing elit. Numquam architecto, ex veritatis"
                            >
                                <figure>
                                    <img
                                        src="assets/images/g8.jpg"
                                        class="img-responsive"
                                        alt=""
                                    />
                                </figure>
                            </a>
                        </div>
                        <div class="product">
                            <a
                                href="assets/images/g1.jpg"
                                data-lightbox="example-set"
                                data-title="Lorem ipsum dolor sit amet consectetur adipisicing elit. Numquam architecto, ex veritatis"
                            >
                                <figure>
                                    <img
                                        src="assets/images/g1.jpg"
                                        class="img-responsive"
                                        alt=""
                                    />
                                </figure>
                            </a>
                        </div>
                        <div class="product">
                            <a
                                href="assets/images/g2.jpg"
                                data-lightbox="example-set"
                                data-title="Lorem ipsum dolor sit amet consectetur adipisicing elit. Numquam architecto, ex veritatis"
                            >
                                <figure>
                                    <img
                                        src="assets/images/g2.jpg"
                                        class="img-responsive"
                                        alt=""
                                    />
                                </figure>
                            </a>
                        </div>
                        <div class="product">
                            <a
                                href="assets/images/g3.jpg"
                                data-lightbox="example-set"
                                data-title="Lorem ipsum dolor sit amet consectetur adipisicing elit. Numquam architecto, ex veritatis"
                            >
                                <figure>
                                    <img
                                        src="assets/images/g3.jpg"
                                        class="img-responsive"
                                        alt=""
                                    />
                                </figure>
                            </a>
                        </div>
                        <div class="product">
                            <a
                                href="assets/images/g4.jpg"
                                data-lightbox="example-set"
                                data-title="Lorem ipsum dolor sit amet consectetur adipisicing elit. Numquam architecto, ex veritatis"
                            >
                                <figure>
                                    <img
                                        src="assets/images/g4.jpg"
                                        class="img-responsive"
                                        alt=""
                                    />
                                </figure>
                            </a>
                        </div>
                    </div>
                </section>

                <section id="content3" class="tab-content text-left">
                    <div class="d-grid grid-col-3">
                        <div class="product">
                            <a
                                href="assets/images/g5.jpg"
                                data-lightbox="example-set"
                                data-title="Lorem ipsum dolor sit amet consectetur adipisicing elit. Numquam architecto, ex veritatis"
                            >
                                <figure>
                                    <img
                                        src="assets/images/g5.jpg"
                                        class="img-responsive"
                                        alt=""
                                    />
                                </figure>
                            </a>
                        </div>
                        <div class="product">
                            <a
                                href="assets/images/g6.jpg"
                                data-lightbox="example-set"
                                data-title="Lorem ipsum dolor sit amet consectetur adipisicing elit. Numquam architecto, ex veritatis"
                            >
                                <figure>
                                    <img
                                        src="assets/images/g6.jpg"
                                        class="img-responsive"
                                        alt=""
                                    />
                                </figure>
                            </a>
                        </div>
                        <div class="product">
                            <a
                                href="assets/images/g7.jpg"
                                data-lightbox="example-set"
                                data-title="Lorem ipsum dolor sit amet consectetur adipisicing elit. Numquam architecto, ex veritatis"
                            >
                                <figure>
                                    <img
                                        src="assets/images/g7.jpg"
                                        class="img-responsive"
                                        alt=""
                                    />
                                </figure>
                            </a>
                        </div>
                    </div>
                </section>

                <section id="content4" class="tab-content text-left">
                    <div class="d-grid grid-col-3">
                        <div class="product">
                            <a
                                href="assets/images/g8.jpg"
                                data-lightbox="example-set"
                                data-title="Lorem ipsum dolor sit amet consectetur adipisicing elit. Numquam architecto, ex veritatis"
                            >
                                <figure>
                                    <img
                                        src="assets/images/g8.jpg"
                                        class="img-responsive"
                                        alt=""
                                    />
                                </figure>
                            </a>
                        </div>
                        <div class="product">
                            <a
                                href="assets/images/g1.jpg"
                                data-lightbox="example-set"
                                data-title="Lorem ipsum dolor sit amet consectetur adipisicing elit. Numquam architecto, ex veritatis"
                            >
                                <figure>
                                    <img
                                        src="assets/images/g1.jpg"
                                        class="img-responsive"
                                        alt=""
                                    />
                                </figure>
                            </a>
                        </div>
                    </div>
                </section>
            </div>
        </div>
        <!-- Products4 block -->
    </div>
    <section class="services-12" id="experience">
        <div class="form-12-content">
            <div class="container">
                <div class="grid grid-column-2 ">
                    <div class="column1">
                        <h3 class="mb-5">Experiences</h3>
                        <div class="experience-top">
                            <h5>2018 - now</h5>
                            <h4>Fulltime Freelancer</h4>
                            <p class="my-3 text-white">
                                Sed ut perspiciatis unde omnis iste natus error
                                sit voluptatem accusantium doloremque
                                laudantium, totam rem aperiam, eaque ipsa quae
                                ab illo inventore veritatis et quasi architecto
                                beatae.
                            </p>
                        </div>
                        <div class="experience-top">
                            <h5>2014 - 2017</h5>
                            <h4>Creative Director at Pixar Studio</h4>
                            <p class="my-3 text-white">
                                Sed ut perspiciatis unde omnis iste natus error
                                sit voluptatem accusantium doloremque
                                laudantium, totam rem aperiam, eaque ipsa quae
                                ab illo inventore veritatis et quasi architecto
                                beatae.
                            </p>
                        </div>
                        <div class="experience-top">
                            <h5>2010 - 2014</h5>
                            <h4>Web Designer at Microsoft</h4>
                            <p class="my-3 text-white">
                                Sed ut perspiciatis unde omnis iste natus error
                                sit voluptatem accusantium doloremque
                                laudantium, totam rem aperiam, eaque ipsa quae
                                ab illo inventore veritatis et quasi architecto
                                beatae.
                            </p>
                        </div>
                    </div>
                    <div class="column2">
                        <h3 class="mb-5">Education</h3>
                        <div class="experience-top">
                            <h5>2010</h5>
                            <h4>Master of Design, University of California</h4>
                            <p class="my-3 text-white">
                                Sed ut perspiciatis unde omnis iste natus error
                                sit voluptatem accusantium doloremque
                                laudantium, totam rem aperiam, eaque ipsa quae
                                ab illo inventore veritatis et quasi architecto
                                beatae.
                            </p>
                        </div>
                        <div class="experience-top">
                            <h5>2007</h5>
                            <h4>Bachelor of Arts, Standford University</h4>
                            <p class="my-3 text-white">
                                Sed ut perspiciatis unde omnis iste natus error
                                sit voluptatem accusantium doloremque
                                laudantium, totam rem aperiam, eaque ipsa quae
                                ab illo inventore veritatis et quasi architecto
                                beatae.
                            </p>
                        </div>
                        <div class="experience-top">
                            <h5>2004</h5>
                            <h4>Specialize App Design, Harvard University</h4>
                            <p class="my-3 text-white">
                                Sed ut perspiciatis unde omnis iste natus error
                                sit voluptatem accusantium doloremque
                                laudantium, totam rem aperiam, eaque ipsa quae
                                ab illo inventore veritatis et quasi architecto
                                beatae.
                            </p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- contact -->
    <section class="w3l-contacts-12" id="contact">
        <div class="contact-top pt-5">
            <div class="container py-md-3">
                <div class="heading text-center mx-auto mb-5">
                    <h3 class="head">Contact Me</h3>
                    <p class="my-3 head">
                        Vestibulum ante ipsum primis in faucibus orci luctus et
                        ultrices posuere cubilia Curae; Nulla mollis dapibus
                        nunc, ut rhoncus turpis sodales quis. Integer sit amet
                        mattis quam.
                    </p>
                </div>
                <div class="row cont-main-top">
                    <!-- contact form -->
                    <div class="contacts12-main col-lg-6 ">
                        <form
                            action="https://sendmail.w3layouts.com/submitForm"
                            method="post"
                            class="main-input"
                        >
                            <div class="top-inputs d-grid">
                                <input
                                    type="text"
                                    placeholder="Name"
                                    name="w3lName"
                                    id="w3lName"
                                    required=""
                                />
                            </div>
                            <input
                                type="email"
                                name="email"
                                placeholder="Email"
                                id="w3lSender"
                                required=""
                            />

                            <textarea
                                placeholder="Message"
                                name="w3lMessage"
                                id="w3lMessage"
                                required=""
                            />
                            <div class="text-right">
                                <button type="submit" class="btn btn-theme2"
                                    >Submit Now</button
                                >
                            </div>
                        </form>
                    </div>
                    <!-- //contact form -->
                    <!-- contact address -->
                    <div class="contact col-lg-6 mt-lg-0 mt-5">
                        <div class="cont-subs">
                            <div class="cont-add">
                                <div class="cont-add-lft">
                                    <span
                                        class="fa fa-map-marker"
                                        aria-hidden="true"
                                    />
                                </div>
                                <div class="cont-add-rgt">
                                    <p class="contact-text-sub">
                                        PO Box 1212, London, UK
                                    </p>
                                </div>
                            </div>
                            <div class="cont-add add-2">
                                <div class="cont-add-lft">
                                    <span
                                        class="fa fa-envelope"
                                        aria-hidden="true"
                                    />
                                </div>
                                <div class="cont-add-rgt">
                                    <a href="mailto:info@example.com">
                                        <p class="contact-text-sub">
                                            info@example.com
                                        </p>
                                    </a>
                                </div>
                            </div>
                            <div class="cont-add">
                                <div class="cont-add-lft">
                                    <span
                                        class="fa fa-phone"
                                        aria-hidden="true"
                                    />
                                </div>
                                <div class="cont-add-rgt">
                                    <a href="tel:+7-800-999-800">
                                        <p class="contact-text-sub">
                                            +7-800-999-800
                                        </p>
                                    </a>
                                </div>
                            </div>
                            <div class="cont-add add-3">
                                <div class="cont-add-lft">
                                    <span
                                        class="fa fa-file-pdf-o"
                                        aria-hidden="true"
                                    />
                                </div>
                                <div class="cont-add-rgt">
                                    <a href="#!">
                                        <p class="contact-text-sub">
                                            Download Resume
                                        </p>
                                    </a>
                                </div>
                            </div>
                        </div>
                    </div>
                    <!-- //contact address -->
                </div>
            </div>
        </div>
    </section>
    <!-- //contact -->
    <!-- grids block 5 -->
    <section class="w3l-footer-29-main" id="footer">
        <div class="footer-29 text-center">
            <div class="container">
                <div class="main-social-footer-29">
                    <a href="#facebook" class="facebook"
                        ><span class="fa fa-facebook" /></a
                    >
                    <a href="#twitter" class="twitter"
                        ><span class="fa fa-twitter" /></a
                    >
                    <a href="#instagram" class="instagram"
                        ><span class="fa fa-instagram" /></a
                    >
                    <a href="#google-plus" class="google-plus"
                        ><span class="fa fa-google-plus" /></a
                    >
                    <a href="#linkedin" class="linkedin"
                        ><span class="fa fa-linkedin" /></a
                    >
                </div>
                <div class="bottom-copies text-center">
                    <p class="copy-footer-29">
                        Russell ❤️ {currentYear}
                    </p>
                </div>
            </div>
        </div>
        <!-- move top -->
        <button onclick="topFunction()" id="movetop" title="Go to top">
            <span class="fa fa-angle-up" />
        </button>
        <script>
            // When the user scrolls down 20px from the top of the document, show the button
            window.onscroll = function () {
                scrollFunction();
            };

            function scrollFunction() {
                if (
                    document.body.scrollTop > 20 ||
                    document.documentElement.scrollTop > 20
                ) {
                    document.getElementById("movetop").style.display = "block";
                } else {
                    document.getElementById("movetop").style.display = "none";
                }
            }

            // When the user clicks on the button, scroll to the top of the document
            function topFunction() {
                document.body.scrollTop = 0;
                document.documentElement.scrollTop = 0;
            }
        </script>
        <!-- /move top -->
    </section>
    <!-- // grids block 5 -->
</main>
