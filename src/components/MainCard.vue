<template>
    <div class="wrapper">
        <div class="main-container">
            <div class="container-one">
                <div class="profile">
                    <img src="../assets/jeff.jpg" alt="">
                    <h3>Jefferson S. Casquejo</h3>
                    <p>SOFTWARE DEVELOPER</p>
                </div>
                <div class="social-link">
                    <div class="link">
                        <a href="https://github.com/Ahjin19" target="blank">
                            <img src="../assets/Diffraction icon.jpg" alt="">
                            <h2>GITHUB</h2>
                        </a>
                    </div>
                    <div class="link">
                        <a href="https://www.facebook.com/jeff.bryant.902" target="blank"> 
                            <img src="../assets/fb.jpg" alt="">
                            <h2>FACEBOOK</h2>
                        </a>
                    </div>
                    <div class="link">
                        <a href="https://www.instagram.com/ambot._nimo/" target="blank">
                            <img src="../assets/insta.jpg" alt="">
                            <h2>INSTAGRAM</h2>
                        </a>
                    </div>
                    <div class="link">
                        <a href="https://www.tiktok.com/@1unknowna9" target="blank">
                            <img src="../assets/tiktok.jpg" alt="">
                            <h2>TIKTOK</h2>
                        </a>
                    </div>
                </div>
            </div>
            <div class="container-two">
                <div class="about me ">
                    <h1>About Me</h1>
                    <p>Jefferson S. Casquejo, 20 years old from San Miguel, Cordova, Cebu.</p>
                    <p>I am an organised, efficient and hard working person, and am willing to discover and accept new ideas which can be put into practice effectively. I am a good listener and learner, able to communicate well with a group and on an individual level. I am able to motivate and direct my talents and skills to meet objectives.</p>
                    <div class="Language-Section">
                        
                        <h1>Favorite Subject's</h1>
                        <div class="logos">
                            <img src="../assets/accounting.jpg" alt="">
                            <img src="../assets/programming.jpg" alt="">
                            <img src="../assets/sci.jpg" alt="">
                            <div class="button-container">
                                <div class="project-button">
                                    <a href="">Contact Number : 09309342253</a>
                                </div>
                                <div class="project-button">
                                    <a href="">EMAIL: jeffethan19@gmail.com</a>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {

}
</script>


<style scoped>
.wrapper {
    display: flex;
    justify-content: center;
}

img {
    height: 40px;
}

.main-container {
    display: flex;
    flex-direction: center; /* Change flex-direction to column for smaller screens */
    background-color: rgb(19, 215, 241);
    border-radius: 10px;
    width: 100%; /* Adjust width for smaller screens */
    max-width: 1300px; /* Add max-width to prevent container from stretching too wide */
    margin: 5px ; /* Center the container */
    background-color: rgb(78, 10, 117);
    box-shadow: 0px 3px 8px rgba(0, 0, 0, 10);
    padding: 10px; /* Add padding */
}

.container-one {
    background-color: rgb(220, 252, 240);
    width: 70%; /* Take full width */
    padding: 10px; /* Add padding */
    border-radius: 35px;
    margin-bottom: 20px; /* Add margin-bottom for spacing */
    box-shadow: 0px 3px 8px rgba(0, 0, 0, 0.5);
}

.profile img {
    height: 120px; /* Adjust height for profile image */
    border-radius: 50%; /* Make the profile image circular */
    box-shadow: 0px 3px 8px rgba(0, 0, 0, 10);
}

.link a {
    text-decoration: none;
    color: #080808;
    font-size: 14px; /* Increase font size for links */
    margin-bottom: 10px; /* Add margin bottom for spacing */
    display: block; /* Display links as block elements */
    
}

.link img {
    height: 80px; /* Adjust height for social media icons */
    box-shadow: 0px 3px 8px rgba(0, 0, 0, 100);
    border-radius: 50%;
}

.container-two {
    background-color: rgb(232, 251, 252);
    margin:1%;
    width: 100%; 
    height: 95%;
    padding: 5px; 
    border-radius: 30px;
    box-shadow: 0px 3px 8px rgba(0, 0, 0, 10);
}

.about-me {
    text-align: center; /* Center align the text */
    margin-bottom: 20px; /* Add margin bottom for spacing */
}

.logos img {
    height: 120px; /* Adjust height for language logos */
    margin-right: 20px; /* Add margin-right for spacing between logos */
    box-shadow: 0px 3px 8px rgba(0, 0, 0, 100);
}
   

.button-container {
    display: flex;
    flex-wrap: wrap;
    justify-content: center; 
}

.project-button {
    background-color: #942ed3;
 
    padding: 10px 20px; 
    margin: 50px; 
    box-shadow: 0px 3px 8px rgba(0, 0, 0, 100);
}

.project-button a {
    text-decoration: none;
    color: #000407;
    font-size: 20x;
}

@media only screen and (min-width: 880px) {
    .main-container {
        width: 80%; 
    }
}
</style>
