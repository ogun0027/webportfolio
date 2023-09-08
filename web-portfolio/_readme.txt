CHALLENGES

I had 2 major challenges during the development of my web portfolio.

The first challenge I faced was how to change the layout of the contents in 'Services' page. The images were too large and overlapped even though I specified 6 columns for each one using a class of ".col-md-6" in the <div> containing the contents. However, I was able to solve this by adding a class of ".col-12" to each of the <img> tags. Please find the code below:

 <div class="container">
        <div class="row">
            <div class="col-md-6 mt-5">
                <a class="text-decoration-none text-dark" href="#">
                    <h2 class="text-center">Photography</h2>
                </a>
                <img class="col-12" src="wp-images/me.jpg" alt="image">
            </div>
            <div class="col-md-6 mt-5">
                <a class="text-decoration-none text-dark" href="#">
                    <h2 class="text-center">Videography</h2>
                </a>
                <img class="col-12" src="wp-images/woman-659350_1920.jpg" alt="image">
            </div>
        </div>
    </div>


The second challenge I had was the usage of a toggler for mobile view. The toggler was displayed but it would not drop down the menu and I could not figure out why. Unfortunately, I was unable to overcome this.

Please find the code below:

<div class="collapse navbar-collapse" id="MobileTog">
        <div class="navbar-nav ml-auto">
            <a class="nav-link active" href="#">Home</a>
            <a class="nav-link" href="#">About</a>
            <a class="nav-link" href="#">Services</a>
            <a class="nav-link" href="#">Contact</a>
        </div>
    </div>
    <button class="navbar-toggler" data-target="#MobileTog" data-toggle="collapse">
        <span class="navbar-toggler-icon" ></span>

    </button>
</nav>




ASSETS & RESOURCES USED

Framework: Bootstrap
Images (except for the image for 'Photography' which is mine): https://pixabay.com/


WHAT I LEARNT

The one thing that I learnt by creating my web portfolio is that even though Bootstrap is a great framework to build responsive websites at a very fast speed, it has limitations. One of the limitations being the creation of border radius. One does not have the freedom to choose a radius size like in the case of the form background that I developed in comparison to the one I designed in Adobe XD. A developer can only use a class of .rounded with no option for sizes.





