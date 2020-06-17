# responsive-portfolio

The goal of the Responsive Portfolio project was to create our first portfolio site while using Bootstrap. The site was to have a consistent nav bar across all pages, a responsive layout, and responsive images. The purpose is to ensure the site is viewable on every size screen and browser.

## Getting Started

1. Log into GitLab > UCB-Coding-Bootcamp > UCB-BER-FSF-FT-06-2020-U-C
2. Navigate to CSS Homework (click) 
3. Open VS Code or similar program and follow provided instructions.

### Prerequisites

* Visual Studio Code https://code.visualstudio.com/
* Bootstrap https://getbootstrap.com/

### Execution

* Created a consistent navbar
```
    <nav class="navbar navbar-expand-lg navbar-light bg-success">
        <a class="navbar-brand" href="index.html">Joe Davis</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
          <div class="navbar-nav ml-auto">
            <a class="nav-item nav-link active" href="index.html">About <span class="sr-only">(current)</span> </a>
            <a class="nav-item nav-link" href="portfolio.html">Portfolio</a>
            <a class="nav-item nav-link" href="contact.html">Contact</a>
          </div>
        </div>
      </nav>
```      
* Created contact page with a form from Bootstrap
```
<div class="container mt-5"  >
        <form class="row"><br>
          <div class="col-sm-6">
            <h2 class="text-success">Contact</h2><br><hr>
            <div class="form-group">
              <label for="exampleFormControlInput1">Email address</label>
              <input type="email" class="form-control" id="exampleFormControlInput1" placeholder="name@example.com">
            </div>
            <div class="form-group">
              <label for="exampleFormControlSelect2">Name</label>
              <input type="Name" class="form-control" id="exampleFormControlInput1" placeholder="John Smith">
            </div>
            <div class="form-group">
              <label for="exampleFormControlTextarea1">Message</label>
              <textarea class="form-control" id="exampleFormControlTextarea1" rows="4"></textarea><br>
              <button type="button" class="btn btn-success">Submit</button>
            </div>
          </div>
        </form>
      </div>
```      
* Created responsive About Me page with text moving around image (index.html)
```
    <div class="container">
      <div class="row">
        <div class="col-sm-9">
          <h2 class="text-success">About Me</h2><hr>
        </div>
        <div class="row"></div>
          <div class="col-sm-6">  
            <img class="img img-thumbnail" src="https://i.pinimg.com/236x/0e/68/ed/0e68eda6243faa5f754b1cfb2b04846d.jpg" alt="SF Giants"> 
          </div>
          <div class="col-sm-3">
            <p>I am a U.S. Army veteran who spent my post-military career in relationship management roles.  I'm currently working to become a full stack developer which will give me a tangible skill to utilize for the remainder of my career.</p>
            <p> I am originally from San Mateo, California, but now I live in Las Vegas, Nevada. I am married with a 4 year old son and a 1 month old daughter.</p>
          </div>
      </div>    
    </div>
```
* Created Portfolio page with responsive images
```
<div class="container">
        <div class="row">
          <div class="col-sm-9">
            <h2 class="text-success mt-5">Portfolio</h2><hr>
              <div class="row">
                <div class="col-sm-6 col-md-6 mt-3">
                  <div class="box skyblue"></div> 
                  <img class="img img-thumbnail" src="https://i.picsum.photos/id/871/200/300.jpg?hmac=wXN1u0NeBnK8vCkjkJXzoTfZn6F0JBzgOpCdmRGXsw0" alt="cliffs">
                </div>
                <div class="col-sm-6 col-md-6 mt-3">
                  <div class="box skyblue"></div>
                  <img class="img img-thumbnail" src="https://i.pinimg.com/236x/0e/68/ed/0e68eda6243faa5f754b1cfb2b04846d.jpg" alt="SF Giants">
                </div>
              </div>        
```
* Ensured links in navbar were working
```
<a class="navbar-brand" href="index.html">Joe Davis</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
          <div class="navbar-nav ml-auto">
            <a class="nav-item nav-link active" href="index.html">About <span class="sr-only">(current)</span> </a>
            <a class="nav-item nav-link" href="portfolio.html">Portfolio</a>
            <a class="nav-item nav-link" href="contact.html">Contact</a>
```


## Built With

* [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
* [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)
* [Javascript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

## Deployed Link

* [https://jdavis3333.github.io/responsive-portfolio/](#)


## Authors

* Joe Davis 

- [Link to Github](https://github.com/jdavis3333)
- [Link to LinkedIn](https://www.linkedin.com/in/joe-davis-a8380232/)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License 

## Acknowledgments

* © 2019 Trilogy Education Services, a 2U, Inc. brand. All Rights Reserved.