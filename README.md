# G3 ARCHITECTS
- welcome to My website
- A website Landing Page create
# files
```index.html```
```styles.css```
# Folder
```styles```
# Figma
- figma file (https://www.figma.com/design/K2Zjh4C5YVdVaHRrHPTa8i/g3-architects?node-id=2-2&t=4UPmIp5IMVTt00IM-0)

# Files
- css
```

.work-sans-font {
  font-family: "Work Sans", sans-serif;
  font-optical-sizing: auto;
  font-weight: 400;
  font-style: normal;
}

/* shared style */
.display-flex{
    display: flex;
}
/* dark-2 */
.text-gray{
    color: #424242;
}
.bg-light{
    background-color: rgba(255, 144, 14, 0.1);
}
/* dark-3 */
.text-light-gray{
    color: #727272;
}

main {
    max-width: 1440px;
}

.brand{
    font-weight: bold;
    font-size: 3rem;
}

.text-primary{
    color: #FF900E;
}
.btn-primary{
    background-color: #FF900E;
    color: white;
    padding: 20px 25px;
    font-size: 1.25rem;
    font-weight: 600;
    border-radius: 8px;
    border: none;
}

main > section {
    margin-top: 130px;
}

.section-title{
    font-size: 2.8rem;
    font-weight: 700;
}


/* some facts styles */
.fact-card{
    border: 1px solid #FF900E;
    width: 240px;
    height: 240px;
    margin: 24px 24px;
    border-radius: 8px;
    text-align: center;
    align-items: center;
    justify-content: center;
}

.fact-description{
    max-width: 540px;
}

.fact-number{
    font-size: 2.8rem;
    font-weight: 600;
    margin-top: 5px;
    margin-bottom: 10px;
}

.fact-name{
    font-size: 1.25rem;
    font-weight: 600;
    margin-top: 10px;
}

.facts-container{
    display: grid;
    grid-template-columns: repeat(4, 1fr);
}

/* future section styles */
.futures{
    margin-top: 169px;
}

#future-section-title{
    border-left: 5px solid #FF900E;
    padding-left: 21px;
}

.future-description{
    max-width:569px;
}

.future-title{
    font-weight: 600;
    font-size: 1.25rem;
}

.future-card{
   padding: 30px;
   box-shadow: 0 4px 30px 0 rgba(0, 0, 0, 0.06);
   margin-bottom: 20px;
   border-radius: 8px;
   
}

.futures{
    margin: 240px 240px;
    
}

/* sponsor styles */
.sponsor-info{
    max-width: 540px;
    margin: 50px auto;
    text-align: center;
}

.sponsor-companies{
    display: grid;
    grid-template-columns: repeat(5, 1fr);
    align-items: center;
    justify-content: center;
}

/* Navbar style */
.Navbar{
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.nav-item{
    list-style: none;
    margin-right: 30px;
}

.nav-link{
    text-decoration: none;
    font-weight: 500;
}

.Navbar , .banner{
    max-width: 1440px;
    margin-left: 228px;
    margin-right: 240px;
    
}

/* Banner styles */
.banner-content{
    max-width: 850px;
    margin: 0px auto;
    text-align: center;
    align-items: center;
    margin-bottom: 50px;
    align-self: center;
    
}
.banner-title{
    font-size: 4rem;
}

.banner-image{
    width: 100%;
}
/* Teams styles */

.teams{
    align-items: center;
;
}

.team-sec-container{
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 24px;
}

.our-futures{
    margin-left:  130px;
    max-width: 530px;
}

#quick-list{
    font-weight: 500;
}

/* footer styles */
.footer{
    margin-top: 130px;
    background-color: #FFF4E7;
    padding-left: 410px;
    padding-right: 410px;
    padding-top: 39px;
    padding-bottom: 38px;
}

.footer-description{
    font-size: 20px;
    text-align: center;
    display: flexbox;
}
```
- html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>G3 architects</title>
    <link rel="stylesheet" href="styles/styles.css">
    <style>
@import url('https://fonts.googleapis.com/css2?family=Work+Sans:ital,wght@0,100..900;1,100..900&display=swap');
</style>
</head>
<body class="work-sans-font">
    <header class="bg-light">
        <nav class="Navbar display-flex">
             <h3 class="brand">G3 Architects</h3>
             <ul class="nav-links display-flex">
                 <li class="nav-item"><a href="" class="nav-link text-gray display-flex">About</a></li>
                 <li class="nav-item"><a href="" class="nav-link text-gray display-flex">Home</a></li>
                 <li class="nav-item"><a href="" class="nav-link text-gray display-flex">Contact Us</a></li>
                 <li class="nav-item"><a href="" class="nav-link text-gray display-flex">Login</a></li>
                </ul>
        </nav>
        <div class="banner">
            <div class="banner-content">
                <h1 class="banner-title">Brand New Group of Architects </h1>
            <p class="banner-description">There are many variations of passages of Lorem Ipsum available, but the majority have suffered alteration in some form, by injected humour, or randomised words which don't look even</p>
            <button class="btn-primary">Explore me</button>
            </div>
            <img class="banner-image" src="images/banner.png">
        </div>
    </header>
    <main>
        <section class="teams">
        <section class="teams display-flex">
            <div class="team-sec-container">
                <img src="images/team1.png" alt="">
                <img src="images/team2.png" alt="">
                <img src="images/team3.png" alt="">
                <img src="images/team4.png" alt="">
            </div>
            <div class="our-futures">
                <h3 class="section-title"><span id="quick-list" class="text-light-gray">Quick list</span> of Our <span class="text-primary">Features</span></h3>
                <p class="future-description text-light-gray">There are many variations of passages of Lorem Ipsum available, but the majority have suffered alteration in some form, by injected humour, or randomised words which don't look even</p>
                <button class="btn-primary">Explore more</button>
            </div>
        </section>
         <!-- some facts -->
          <section class="some-facts">
            <h3 class="section-title">Some Facts</h3>
            <p class="text-light-gray">There are many variations of passages of Lorem Ipsum available, but the majority have suffered alteration.</p>
            <div class="facts-container">
                <!-- .fact-card*4>img.fact-icon+h4.fact-number+h5.fact-name -->
                 <div class="fact-card display-flex">
                    <div>
                        <img src="images/icons/ribon.png" alt="" class="fact-icon">
                    <h4 class="fact-number">54</h4>
                    <h5 class="fact-name text-light-gray">Awards Winnings</h5>
                    </div>
                 </div>
                 <div class="fact-card display-flex">
                    <div>
                        <img src="images/icons/projects.png" alt="" class="fact-icon">
                    <h4 class="fact-number">1458</h4>
                    <h5 class="fact-name text-light-gray">Project Finished</h5>
                    </div>
                 </div>
                 <div class="fact-card display-flex">
                    <div>
                        <img src="images/icons/customers.png" alt="" class="fact-icon">
                    <h4 class="fact-number">590</h4>
                    <h5 class="fact-name text-light-gray">Clients worked</h5>
                    </div>
                 </div>
                 <div class="fact-card display-flex">
                    <div>
                        <img src="images/icons/email.png" alt="" class="fact-icon">
                    <h4 class="fact-number">22578</h4>
                    <h5 class="fact-name text-light-gray">Email Send</h5>
                    </div>
                 </div>
            
            </div>
          </section> 
             <!-- our sponsors -->
              <section class="our-sponsors">
                <div class="sponsor-info">
                    <h3 class="section-title">Our Sponsors</h3>
                    <p class="text-light-gray">There are many variations of passages of Lorem Ipsum available, but the majority have suffered alteration.</p>
                </div>
                <div class="sponsor-companies">
                    <img src="images/sponsors/spotify.png" alt="">
                    <img src="images/sponsors/amazon.png" alt="">
                    <img src="images/sponsors/google.png" alt="">
                    <img src="images/sponsors/telerama.png" alt="">
                    <img src="images/sponsors/figma.png" alt="">
                </div>
              </section>
        </main>
    <footer class="footer">
         <p class="footer-description">All rights reserved copyright@2023 startup landing page design</p>
    </footer>
</body>
</html>
```
