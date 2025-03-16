# Ex02 Commercial Website
## Date:16-03-2025
## Reg no:212223220103

## AIM
To create a commercial website using CSS Flexbox.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for Homepage, Products / Services, About Us, Contact Details and User Account.

### STEP 5
Include social media links at the footer with copyright information.

### STEP 6
Define global styles for fonts, colors, and layout.

### STEP 7
Style the header, navigation bar, and sections.

### STEP 8
Use Flexbox for layout design.

### STEP 9
Add hover effects and transitions for interactivity.

### STEP 10
Add Images and Media.

### STEP 11
Use optimized images for a professional look.

### STEP 12
Open the HTML file in a browser to check layout and functionality.

### STEP 13
Fix styling issues and refine content placement.

### STEP 14
Deploy the website.

### STEP 15
Upload to GitHub Pages for free hosting.

## PROGRAM
#home.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>commercial website</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <style>
        body
        {
            background-image:url(sk.jpg);
            background-size: cover;
            background-repeat: no-repeat;
            background-position: center center;
            height: 100vh;
            margin: 0;
        }
        .csk{
            display: flex;
            flex-direction: column;
            align-items: center;
            gap: 20px;
            padding: 150px;

        }
        .f1{
            color: aliceblue;
        }
    </style>
</head>
<body>
    <header class="p-3 text-bg-dark">
        <div>
            <h1>COMMERCIAL WEBSITE</h1>
        </div>
        <div class="container">
          <div class="d-flex flex-wrap align-items-center justify-content-center justify-content-lg-start">
            <a href="/" class="d-flex align-items-center mb-2 mb-lg-0 text-white text-decoration-none">
              <svg class="bi me-2" width="40" height="32" role="img" aria-label="Bootstrap"><use xlink:href="#bootstrap"></use></svg>
            </a>
    
            <ul class="nav col-12 col-lg-auto me-lg-auto mb-2 justify-content-center mb-md-0">
              <li><a href="e2.html" class="nav-link px-2 text-secondary">Home</a></li>
              <li><a href="ff.html" class="nav-link px-2 text-white">Features</a></li>
              <li><a href="ff3.html" class="nav-link px-2 text-white">FAQs</a></li>
              <li><a href="ff4.html" class="nav-link px-2 text-white">About</a></li>
            </ul>
    
            <form class="col-12 col-lg-auto mb-3 mb-lg-0 me-lg-3" role="search">
              <input type="search" class="form-control form-control-dark text-bg-dark" placeholder="Search..." aria-label="Search">
            </form>
    
            <div class="text-end">
              <button type="button" class="btn btn-outline-light me-2">Login</button>
              <button type="button" class="btn btn-warning">Sign-up</button>
              <a href="#" class="btn">Get Started</a>
            </div>
          </div>
        </div>
      </header>
      <div class="csk">
        <h1 class="f1"> WELCOME TO OUR COMMERCIAL WEBSITE</h1>
        <p class="f1">Your success is our priority. Explore our services today!</p>
        <p class="f1">Explore our services and be a part of an innovative business solution designed just for you.</p>
        <a href="#" class="btn btn-warning">Get Started</a>
      </div>
    
</body>
</html>
```
#Features.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>commercial website</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <style>
        body
        {
            background-image:url(sk.jpg);
            background-size: cover;
            background-repeat: no-repeat;
            background-position: center center;
            height: 100vh;
            margin: 0;
        }
        .rcb{
            display: flex;
            flex-direction: column;
            align-items: center;
            
            padding: 30px;

        }
        .f1{
            color: aliceblue;
        }
        .aaa{
            display: flex;
            flex-direction: column;
            align-items: center;
           
        }
    </style>
</head>
<body>
    <header class="p-3 text-bg-dark">
        <div>
            <h1>COMMERCIAL WEBSITE</h1>
        </div>
        
        <div class="container">
          <div class="d-flex flex-wrap align-items-center justify-content-center justify-content-lg-start">
            <a href="/" class="d-flex align-items-center mb-2 mb-lg-0 text-white text-decoration-none">
              <svg class="bi me-2" width="40" height="32" role="img" aria-label="Bootstrap"><use xlink:href="#bootstrap"></use></svg>
            </a>
    
            <ul class="nav col-12 col-lg-auto me-lg-auto mb-2 justify-content-center mb-md-0">
              <li><a href="e2.html" class="nav-link px-2 text-white">Home</a></li>
              <li><a href="ff.html" class="nav-link px-2 text-secondary">Features</a></li>
              <li><a href="ff3.html" class="nav-link px-2 text-white">FAQs</a></li>
              <li><a href="ff4.html" class="nav-link px-2 text-white">About</a></li>
            </ul>
    
            <form class="col-12 col-lg-auto mb-3 mb-lg-0 me-lg-3" role="search">
              <input type="search" class="form-control form-control-dark text-bg-dark" placeholder="Search..." aria-label="Search">
            </form>
    
            <div class="text-end">
              <button type="button" class="btn btn-outline-light me-2">Login</button>
              <button type="button" class="btn btn-warning">Sign-up</button>
            </div>
          </div>
        </div>
      </header>
      <div class="aaa">
        <div class="col-md-6 ">
            <div class="row g-0 border rounded overflow-hidden flex-md-row mb-4 shadow-sm h-md-250 position-relative">
              <div class="col p-4 d-flex flex-column position-static">
                <strong class="d-inline-block  f1">World</strong>
                <h3 class="mb-0 f1">Featured post</h3>
                <div class="mb-1  f1">Nov 12</div>
                <p class="card-text mb-auto f1">goal of our company towards future</p>
                <a href="#" class="icon-link gap-1 icon-link-hover stretched-link f1">
                  Continue reading
                  <svg class="bi"><use xlink:href="#chevron-right"></use></svg>
                </a>
              </div>
              <div class="col-auto d-none d-lg-block">
                <img src="c:\Users\admin\Documents\web dev\html\exp-2\fff.jpg" alt="Featured Image" width="300" height="500" class="img-fluid">
              </div>
            </div>
          </div>
      </div>
      <div class="rcb">
        <h1 class="f1">THE EXCLUSIVE FEATURES THAT WE OFFER</h1>
        <p class="f1">
            <ul>
                <li class="f1">User-Friendly Interface</li>
                <li class="f1"> E-Commerce Features</li>
                <li class="f1">Product catalog with detailed descriptions & images</li>  
                <li class="f1">Shopping cart & wishlist</li>   
                <li class="f1">Secure checkout process</li> 
                <li class="f1">Payment & Security</li>   
            </ul>
            
            
        </p>
        <a href="#" class="btn btn-warning">More Features</a>
      </div>
    
</body>
</html>
```
#FAQ.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>commercial website</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <style>
        body
        {
            background-image:url(sk.jpg);
            background-size: cover;
            background-repeat: no-repeat;
            background-position: center center;
            height: 100vh;
            font-family: Arial, sans-serif;
            
            margin: 0;
            padding: 0;
        }

        .container1 {
            width: 80%;
            max-width: 1000px;
            margin: auto;
            padding: 20px;
            background: white;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            margin-top: 50px;
            border-radius: 5px;
        }
        .aa {
            text-align: center;
        }
        .faq {
            margin-bottom: 20px;
        }
        .question {
            background: #333;
            color: white;
            padding: 15px;
            cursor: pointer;
            border-radius: 5px;
        }
        .answer {
            display: none;
            padding: 15px;
            background: #f9f9f9;
            border-radius: 5px;
            margin-top: 5px;
        }
    </style>
</head>
<body>
    <header class="p-3 text-bg-dark">
        <div>
            <h1>COMMERCIAL WEBSITE</h1>
        </div>
        <div class="container">
          <div class="d-flex flex-wrap align-items-center justify-content-center justify-content-lg-start">
            <a href="/" class="d-flex align-items-center mb-2 mb-lg-0 text-white text-decoration-none">
              <svg class="bi me-2" width="40" height="32" role="img" aria-label="Bootstrap"><use xlink:href="#bootstrap"></use></svg>
            </a>
    
            <ul class="nav col-12 col-lg-auto me-lg-auto mb-2 justify-content-center mb-md-0">
              <li><a href="e2.html" class="nav-link px-2 text-white">Home</a></li>
              <li><a href="ff.html" class="nav-link px-2 text-white">Features</a></li>
              <li><a href="ff3.html" class="nav-link px-2 text-secondary">FAQs</a></li>
              <li><a href="ff4.html" class="nav-link px-2 text-white">About</a></li>
            </ul>
    
            <form class="col-12 col-lg-auto mb-3 mb-lg-0 me-lg-3" role="search">
              <input type="search" class="form-control form-control-dark text-bg-dark" placeholder="Search..." aria-label="Search">
            </form>
    
            <div class="text-end">
              <button type="button" class="btn btn-outline-light me-2">Login</button>
              <button type="button" class="btn btn-warning">Sign-up</button>
            </div>
          </div>
        </div>
      </header>
      <div class="container1">
        <h1 class="aa">Frequently Asked Questions</h1>
        
        <div class="faq">
            <div class="question">What services do you offer?</div>
            <div class="answer">We offer web development, digital marketing, and IT consulting services.</div>
        </div>
        
        <div class="faq">
            <div class="question">How can I contact support?</div>
            <div class="answer">You can contact our support team via email at support@brandname.com or call us at +1234567890.</div>
        </div>
        
        <div class="faq">
            <div class="question">What payment methods do you accept?</div>
            <div class="answer">We accept credit/debit cards, PayPal, and bank transfers.</div>
        </div>
    </div>

    <script>
        document.querySelectorAll('.question').forEach(question => {
            question.addEventListener('click', () => {
                let answer = question.nextElementSibling;
                answer.style.display = answer.style.display === 'block' ? 'none' : 'block';
            });
        });
    </script>
    
</body>
</html>
```
#about.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>commercial website</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <style>
        body
        {
            background-image:url(sk.jpg);
            background-size: cover;
            background-repeat: no-repeat;
            background-position: center center;
            height: 100vh;
            margin: 0;
        }
        .mi{
            display: flex;
            flex-direction: column;
            align-items: center;
            
            padding: 50px;

        }
        .f1{
            color: aliceblue;
        }
    </style>
</head>
<body>
    <header class="p-3 text-bg-dark">
        <div>
            <h1>COMMERCIAL WEBSITE</h1>
        </div>
        <div class="container">
          <div class="d-flex flex-wrap align-items-center justify-content-center justify-content-lg-start">
            <a href="/" class="d-flex align-items-center mb-2 mb-lg-0 text-white text-decoration-none">
              <svg class="bi me-2" width="40" height="32" role="img" aria-label="Bootstrap"><use xlink:href="#bootstrap"></use></svg>
            </a>
    
            <ul class="nav col-12 col-lg-auto me-lg-auto mb-2 justify-content-center mb-md-0">
              <li><a href="e2.html" class="nav-link px-2 text-white">Home</a></li>
              <li><a href="ff.html" class="nav-link px-2 text-white">Features</a></li>
              <li><a href="ff3.html" class="nav-link px-2 text-white">FAQs</a></li>
              <li><a href="ff4.html" class="nav-link px-2 text-secondary">About</a></li>
            </ul>
    
            <form class="col-12 col-lg-auto mb-3 mb-lg-0 me-lg-3" role="search">
              <input type="search" class="form-control form-control-dark text-bg-dark" placeholder="Search..." aria-label="Search">
            </form>
    
            <div class="text-end">
              <button type="button" class="btn btn-outline-light me-2">Login</button>
              <button type="button" class="btn btn-warning">Sign-up</button>
            </div>
          </div>
        </div>
      </header>
      <div class="mi">
        <h2 class="f1">About Our Company</h2>
        <p class="f1">We are dedicated to bringing high-quality products and wellness solutions to our valued customers. Our mission is to make premium goods accessible to everyone at affordable prices.</p>
        <p class="f1">With years of expertise, we ensure that every customer gets the best service, the best deals, and the best experience.</p>
      </div>
      <div class="container">
        <footer class="row row-cols-1 row-cols-sm-2 row-cols-md-5 py-5 my-5 border-top">
          <div class="col mb-3">
            <a href="/" class="d-flex align-items-center mb-3 link-body-emphasis text-decoration-none">
              <svg class="bi me-2" width="40" height="32"><use xlink:href="#bootstrap"></use></svg>
            </a>
            <p class="text-white">© 2024</p>
          </div>
      
          <div class="col mb-3">
      
          </div>
      
          <div class="col mb-3">
            <h5 class="text-white">Section 1</h5>
            <ul class="nav flex-column">
              <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-body-white">Home</a></li>
              <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-body-white">Features</a></li>
              <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-body-white">Pricing</a></li>
              <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-body-white">FAQs</a></li>
              <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-body-white">About</a></li>
            </ul>
          </div>
      
          <div class="col mb-3">
            <h5 class="text-white">Section 2</h5>
            <ul class="nav flex-column">
              <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-body-white">Home</a></li>
              <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-body-white">Features</a></li>
              <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-body-white">Pricing</a></li>
              <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-body-white">FAQs</a></li>
              <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-body-white">About</a></li>
            </ul>
          </div>
      
          <div class="col mb-3">
            <h5 class="text-white">Section 3</h5>
            <ul class="nav flex-column">
              <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-body-white">Home</a></li>
              <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-body-white">Features</a></li>
              <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-body-white">Pricing</a></li>
              <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-body-white">FAQs</a></li>
              <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-body-white">About</a></li>
            </ul>
          </div>
        </footer>
      </div>
    
</body>
</html>
```
## OUTPUT
#1 Home page
![image](https://github.com/user-attachments/assets/c8325aac-cf3c-4572-9940-e4e637188ee3)
#2 Featuers page
![image](https://github.com/user-attachments/assets/730074fd-c3a0-4972-9c9b-b3cf57eae5de)
#3 FAQ page
![image](https://github.com/user-attachments/assets/e2ecdc5d-05e9-424f-bd8b-58f86d26bd1f)
#4 About page
![image](https://github.com/user-attachments/assets/354d6f5e-1ec6-46c3-a402-781865bd387f)





## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
