# Music_page
#HTML

<!DOCTYPE html>
<html>

<head>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous">
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js" integrity="sha384-B4gt1jrGC7Jh4AgTPSdUtOBvfO8shuf57BaghqFfPlYxofvL8/KUEfYiJOMMV+rV" crossorigin="anonymous"></script>
</head>

<body>
    <div id="sectionmusichome">
        <div class="d-flex flex-column justify-content-center">

            <div class="sleep-bg-container">
                <div>
                    <h1 class="sleep-heading">Sleep Music</h1>
                    <p class="sleep-heading">Soothing bettime music to help you fall into a deep and natural sleep</p>
                    <div class="homecardimage">
                        <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/moon-bg.png" class="sleep-image ml-5" />
                        <h1 class="sleep-heading mr-5">Night Island</h1>
                    </div>

                    <p class="sleep-heading">Non stop 8-hours mixes of our most popular sleep audio </p>
                    <div class="sleep-heading">
                        <button class="btn btn-primary" onclick="display('sectiondetailspage')">Get Started</button>

                    </div>

                </div>
            </div>
        </div>
    </div>


    <div id="sectiondetailspage">
        <div class="details-top-container">
        </div>
        <div class="details-bottom-container">
            <h1 class="details-heading">Night Island</h1>
            <p class="details-para">easy the mind into a restful night sleep with these deep amblent tones.</p>
            <p class="details-para">45 minutes</p>
            <h1 class="details-heading">Related</h1>

            <div class="d-flex flex-row">
                <div>
                    <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/moon-clouds-img.png" class="details-image" />
                    <h1 class="details-heading">Moon clouds</h1>
                    <p class="details-para">55 min sleep music</p>
                </div>
                <div>
                    <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/sweet-sleep-img.png" class="details-image" />
                    <h1 class="details-heading">Sweet sleep</h1>
                    <p class="details-para">60 min sleep music</p>
                </div>


            </div>
            <button class="btn btn-primary" onclick="display('sectionmusichome')">Back</button>
        </div>
    </div>


    <script type="text/javascript" src="https://new-assets.ccbp.in/frontend/content/static-ccbp-ui-kit/static-ccbp-ui-kit.js"></script>
</body>

</html>

#css

@import url('https://fonts.googleapis.com/css2?family=Bree+Serif&family=Caveat:wght@400;700&family=Lobster&family=Monoton&family=Open+Sans:ital,wght@0,400;0,700;1,400;1,700&family=Playfair+Display+SC:ital,wght@0,400;0,700;1,700&family=Playfair+Display:ital,wght@0,400;0,700;1,700&family=Roboto:ital,wght@0,400;0,700;1,400;1,700&family=Source+Sans+Pro:ital,wght@0,400;0,700;1,700&family=Work+Sans:ital,wght@0,400;0,700;1,700&display=swap');

.sleep-bg-container {

    background-image: url("https://new-assets.ccbp.in/frontend/static-website/moon-stars-bg.png");
    background-size: cover;
    

}

.sleep-card-container {

    background-color: white;
}

.sleep-heading {

    color: white;
    font-family: Bree Serif;
    text-align: center;
    padding: 20px;
}

.homecardimage {

    margin-left: 100px;
    margin-top: 100px;
}

.sleep-image {

    height: 30vh;
    width: 50vw;
}


.details-top-container {

    background-image: url("https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/clouds-img.png");
    background-size: cover;
    height: 50vh;
}

.details-bottom-container {

    background-color: #03174c;
    background-size: cover;
}

.details-heading {

    color: white;
    font-family: Bree Serif;
}

.details-para {

    color: #98a1bd;
    font-family: Bree Serif;
}

.details-image {

    height: 150px;

}
