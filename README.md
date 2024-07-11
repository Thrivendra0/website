<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gym Website</title>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css"/>
    <style>
        body {
    font-family: 'Arial', sans-serif;
    background-color: #f8f9fa;
}

.navbar-nav .nav-item .nav-link {
    transition: color 0.3s ease;
}

.navbar-nav .nav-item .nav-link:hover {
    color: #f0ad4e;
}

.hero {
    background: url('https://cdn.pixabay.com/photo/2016/03/27/07/08/man-1282232_1280.jpg') no-repeat center center;
    background-size: cover;
    height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
}

.hero .container {
    background: rgba(0, 0, 0, 0.5);
    padding: 50px;
    border-radius: 10px;
}

h2 {
    margin-top: 40px;
    font-size: 2.5em;
    color: #333;
}

.container img {
    max-width: 100%;
    height: auto;
    margin-top: 20px;
    border-radius: 10px;
}

.card {
    border-radius: 10px;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.card:hover {
    transform: scale(1.05);
    box-shadow: 0 10px 20px rgba(0, 0, 0, 0.2);
}
.box1{
 
    width: 400px;
    height: 300px;
    display: inline-block;
    margin-right:200px;
    padding-left:10px;
}
.box2{
   
    width: 300px;
    height: 300px;
    display: inline-block;
    margin-right: 20px;
    padding:20px;
    position: relative;
    top:-7px;
}
#po{
    position: relative;
    left:50px;
    color:white;
    background-color: black;
    border-radius: 100px;
}
.contact{
    color:white;
    background-color: #333;
}
.contact h1{
    position:relative;
    top:5px;
}
.box3{

    width: 200px;
    height: 300px;
    display: inline-block;
    margin:0px auto;
    padding:20px;
    float:right;
    


  
}
.box3 img{
  
    width:50px;
    height:50px;
}


    </style>
</head>
<body>
    <!-- Navigation Bar -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <a class="navbar-brand" href="#">Gym</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav ml-auto">
                <li class="nav-item">
                    <a class="nav-link" href="#male">Male</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#female">Female</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#nutrition">Nutrition</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#products">Products</a>
                </li>
            </ul>
        </div>
    </nav>

    <!-- Hero Section -->
    <header class="hero">
        <div class="container text-center text-white">
            <h1 class="animate_animated animate_fadeInDown">Welcome to Our Gym</h1>
            <p class="animate_animated animate_fadeInUp">Achieve Your Fitness Goals With Us</p>
        </div>
    </header>

    <!-- Content Sections -->
    <div id="male" class="container mt-5">
        <h2 class="animate_animated animate_fadeInLeft">Male Section</h2>
        <p>CFitness Plan for Men
Day 1: Full Body
Push-ups: 3 sets of 10-15 reps
Squats: 3 sets of 15-20 reps
Plank: 3 sets of 30 seconds
Day 2: Rest
Day 3: Upper Body
Pull-ups (or inverted rows if no pull-up bar): 3 sets of 5-10 reps
Dumbbell Shoulder Press: 3 sets of 10-15 reps
Bicep Curls: 3 sets of 10-15 reps
Day 4: Rest
Day 5: Lower Body
Lunges: 3 sets of 10-15 reps per leg
Calf Raises: 3 sets of 20 reps
Glute Bridges: 3 sets of 15 reps
Day 6: Rest
Day 7: Core
Bicycle Crunches: 3 sets of 20 reps
Russian Twists: 3 sets of 20 reps
Leg Raises: 3 sets of 10-15 reps</p>
        <img src="https://media.istockphoto.com/id/1171169127/photo/headshot-of-cheerful-handsome-man-with-trendy-haircut-and-eyeglasses-isolated-on-gray.jpg?s=1024x1024&w=is&k=20&c=XqdEhl6H45-ExavLE79QmwmJRy3VYtnlfOWxTx-oy2k=" class="img-fluid animate_animated animate_zoomIn" alt="Male Section">
    </div>

    <div id="female" class="container mt-5">
        <h2 class="animate_animated animate_fadeInRight">Female Section</h2>
        <p>Fitness Plan for Women
Day 1: Full Body
Bodyweight Squats: 3 sets of 15-20 reps
Push-ups (modified if needed): 3 sets of 10-15 reps
Plank: 3 sets of 30 seconds
Day 2: Rest
Day 3: Lower Body
Lunges: 3 sets of 10-15 reps per leg
Glute Bridges: 3 sets of 15 reps
Side Leg Raises: 3 sets of 15 reps per side
Day 4: Rest
Day 5: Upper Body
Dumbbell Shoulder Press: 3 sets of 10-15 reps
Dumbbell Rows: 3 sets of 10-15 reps per arm
Tricep Dips (using a chair): 3 sets of 10-15 reps
Day 6: Rest
Day 7: Core
Bicycle Crunches: 3 sets of 20 reps
Russian Twists: 3 sets of 20 reps
Leg Raises: 3 sets of 10-15 reps
</p>
        <img src="https://media.istockphoto.com/id/1289220545/photo/beautiful-woman-smiling-with-crossed-arms.jpg?s=1024x1024&w=is&k=20&c=wobHCIC8ARiLxB4rmznE6JixLVRNtHHOzP366loetck=" class="img-fluid animate_animated animate_zoomIn" alt="Female Section">
    </div>

    <div id="nutrition" class="container mt-5">
        <h2 class="animate_animated animate_fadeInLeft">Nutrition Section</h2>
        <p>Content for nutrition section.</p>
        <img src="https://media.istockphoto.com/id/1357522255/photo/shot-of-an-unrecognisable-senior-man-cooking-a-healthy-meal-at-home.jpg?s=1024x1024&w=is&k=20&c=ijw_UU_3j3kzpKPngH11km0x6ZHWrGTyOHWP8HK8Lgs=" class="img-fluid animate_animated animate_zoomIn" alt="Nutrition Section">
    </div>

    <!-- Products Section -->
    <div id="products" class="container mt-5">
        <h2 class="animate_animated animate_fadeInRight">Products</h2>
        <div class="row">
            <div class="col-md-4">
                <div class="card mb-4 animate_animated animate_flipInY">
                    <img src="https://media.istockphoto.com/id/1364650215/photo/tired-young-sportsman-resting-after-gym-workout.webp?s=1024x1024&w=is&k=20&c=5VQ-oQ5tzQDb3_ichXbmwIyCaT6UIDZmoiKDBFJ6Ofo=" class="card-img-top" alt="Product 1">
                    <div class="card-body">
                        <h5 class="card-title">Product 1</h5>
                        <p class="card-text">Description of Product 1.</p>
                        <p class="card-text"><strong>$29.99</strong></p>
                        <a href="#" class="btn btn-primary" onclick="alert('YOU ORDER THIS')">Buy Now</a>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card mb-4 animate_animated animate_flipInY">
                    <img src="https://media.istockphoto.com/id/1396360429/photo/one-caucasian-woman-taking-a-brake-during-outdoor-training-in-the-park-outdoor-gym-resting-on.jpg?s=1024x1024&w=is&k=20&c=ktlxVTg7yUooihpwcIzlCOQC90r1iJWY9-t-CxTDHZk=" class="card-img-top" alt="Product 2">
                    <div class="card-body">
                        <h5 class="card-title">Product 2</h5>
                        <p class="card-text">Description of Product 2.</p>
                        <p class="card-text"><strong>$49.99</strong></p>
                        <a href="#" class="btn btn-primary"  onclick="alert('YOU ORDER THIS')">Buy Now</a>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card mb-4 animate_animated animate_flipInY">
                    <img src="https://media.istockphoto.com/id/1092670800/photo/sport-training-weight-dumbles-on-wooden-ground.jpg?s=1024x1024&w=is&k=20&c=xeAW2Nw1r6ndNjcRMemYFMKQn6P5gsNq6uQ6lDLHuH8=" class="card-img-top" alt="Product 3">
                    <div class="card-body">
                        <h5 class="card-title">Product 3</h5>
                        <p class="card-text">Description of Product 3.</p>
                        <p class="card-text"><strong>$19.99</strong></p>
                        <a href="#" class="btn btn-primary"  onclick="alert('YOU ORDER THIS')">Buy Now</a>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <div class="contact">
       <center> <h1>CONTACT US</h1></center><br>
        <div class="box1">
            <p>Our Office Address:</p>
            <p>12th Apt, Gulhmorg Road, New Delhi-134609, India</p>
            <p><iframe src="https://maps.google.com/maps?width=100%25&amp;height=600&amp;hl=en&amp;q=1%20Grafton%20Street,%20Dublin,%20Ireland+(My%20Business%20Name)&amp;t=&amp;z=14&amp;ie=UTF8&amp;iwloc=B&amp;output=embed"></iframe></p>
        </div>
        <div class="box2">
            Name:<br>
            <input type="name">
            <br>
            Message:<br>
            <input type="textbox">
            <br>
            Email:<br>
            <input type="email">
            <br><br>
            <input id="po" type="submit" value="SUBMIT NOW">
        </div>
        <div class="box3">
            <p>LIKE US ON</p>
            <div class="img">
                <img src="https://www.pngmart.com/files/23/Facebook-Logo-PNG-Isolated-HD.png" onclick="sae()">
            </div>
        </div>

    </div>

    <!-- Scripts -->
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.5.4/dist/umd/popper.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
    <script>
        function sae(){
           document.querySelector('.img').innerHTML="<a href='https://www.facebook.com'>CLICK</a>";
        }
    </script>
</body>
</html>
