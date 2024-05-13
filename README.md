# Project Responsive Web Design using Bootstrap
## Date:

## AIM:
To design a responsive website for a Pharmaceutical Company using Bootstrap.


## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

### Step 5:
Create a HTML file and include the needed Bootstrap components.

### Step 6:
Publish the website in the LocalHost.

## PROGRAM :

```
app.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Pharma</title>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css"  crossorigin="anonymous">
<body>

  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">HURAMA Pharma</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item">
            <a class="nav-link" href="#">Home</a>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle active" href="#" id="aboutUsDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
              About Us
            </a>
            <ul class="dropdown-menu" aria-labelledby="aboutUsDropdown">
              <li><a class="dropdown-item" href="#">FOUNDATION</a></li>
              <li><a class="dropdown-item" href="#">AIM</a></li>
              <li><a class="dropdown-item" href="#">LEADERS</a></li>
            </ul>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="products.html">Products</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="event.html">Events</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="abouT.html">Contact</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
  <section class="hero d-flex align-items-center justify-content-center text-center py-5 mb-5">
    <div class="container">
      <h1>EASY ACCESS TO HEALTHCARE</h1>
      <p class="lead">Our aim is to provide healthcare and medicines to people in remote areas.</p>
      <a href="#" class="btn btn-primary btn-lg">MORE INFO</a>
    </div>
  </section>

  <section class="container">
    <div class="row">
      <div class="col-md-4 mb-4">
        <div class="card">
          <img src="app1.png" class="card-img-top" alt="Image">
          <div class="card-body">
            <h5 class="card-title">UPDATION</h5>
            <p class="card-text">We are prone to update our machines to more enhanced way to make sure of your health needs</p>
          </div>
        </div>
      </div>
      <div class="col-md-4 mb-4">
        <div class="card">
          <img src="app2.png" class="card-img-top" alt="Image">
          <div class="card-body">
            <h5 class="card-title">QUALITY</h5>
            <p class="card-text">Our commitment to quality ensures the safety and cleanliness of rooms to avoid spreading od disease.</p>
          </div>
        </div>
      </div>
      <div class="col-md-4 mb-4">
        <div class="card">
          <img src="app3.png" class="card-img-top" alt="Image">
          <div class="card-body">
            <h5 class="card-title">Patient Care</h5>
            <p class="card-text">We are so kind to our patient.Its our responsibility to take a complete care of them.Every patient is equal to us no matter they are rich or poor.We respect our patients.</p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <footer class="text-center py-3 bg-light">
    <p>&copy; 2024 HURAMA Pharma HARISHA S(212223040063) </p>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p" crossorigin="anonymous"></script>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Our Products</title>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css"  crossorigin="anonymous">
</head>
<body>


  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">HURAMA Pharma</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item">
            <a class="nav-link" href="app.html">Home</a>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle active" href="#" id="aboutUsDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
              About Us
            </a>
            <ul class="dropdown-menu" aria-labelledby="aboutUsDropdown">
              <li><a class="dropdown-item" href="#">FOUNDATION</a></li>
              <li><a class="dropdown-item" href="#">AIM</a></li>
              <li><a class="dropdown-item" href="#">LEADERS</a></li>
            </ul>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="products.html">Products</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="event.html">Events</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="about.html">Contact</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>

  <section class="container py-5">
    <h1 class="text-center mb-4">Our Products</h1>
    <div class="row row-cols-1 row-cols-md-2 row-cols-lg-3 g-4">
      <div class="col">
        <div class="card">
          <img src="pro1.png" class="card-img-top" alt="Product Image">
          <div class="card-body">
            <h5 class="card-title">Neurocalm</h5>
            <p class="card-text">Neurocalm is a medication designed to alleviate symptoms of anxiety and promote relaxation by regulating neurotransmitter activity in the brain. It helps manage anxiety disorders, including generalized anxiety disorder and panic disorder.</p>
            <a href="#" class="btn btn-primary">Know More</a>
          </div>
        </div>
      </div>
      <div class="col">
        <div class="card">
          <img src="pro2.png" class="card-img-top" alt="Product Image">
          <div class="card-body">
            <h5 class="card-title"> CardioClear</h5>
            <p class="card-text">CardioClear is a cardiovascular medication that helps regulate blood pressure and improve heart function. It is commonly prescribed to individuals with hypertension and congestive heart failure to reduce the risk of cardiovascular events such as heart attacks and strokes.</p>
            <a href="#" class="btn btn-primary">Know More</a>
          </div>
        </div>
      </div>
      <div class="col">
        <div class="card">
          <img src="pro3.png" class="card-img-top" alt="Product Image">
          <div class="card-body">
            <h5 class="card-title"> RenewFlex</h5>
            <p class="card-text"> RenewFlex is a joint health supplement formulated to support flexibility and mobility by promoting joint lubrication and cartilage health. It is commonly used to alleviate symptoms of osteoarthritis and improve joint function in individuals experiencing joint stiffness and discomfort.</p>
            <a href="#" class="btn btn-primary">Know More</a>
          </div>
        </div>
      </div>
      </div>
  
  
  </section>

  <footer class="text-center py-3 bg-light">
    <p>&copy; 2024 HURAMA Pharma HARISHA S(212223040063)</p>
  </footer>

</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Events</title>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" crossorigin="anonymous">
</head>
<body>

  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">HURAMA Pharma</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item">
            <a class="nav-link" href="app.html">Home</a>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle active" href="#" id="aboutUsDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
              About Us
            </a>
            <ul class="dropdown-menu" aria-labelledby="aboutUsDropdown">
              <li><a class="dropdown-item" href="#">FOUNDATION</a></li>
              <li><a class="dropdown-item" href="#">AIM</a></li>
              <li><a class="dropdown-item" href="#">LEADERS</a></li>
            </ul>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="products.html">Products</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="event.html">Events</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="about.html">Contact</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>


  <section class="container py-5">
    <h1 class="text-center mb-4">News & Events</h1>
    <div class="row">
      <div class="col-md-3 mb-2">
        <div class="card">
          <img src="eve1.png" class="card-img-top" alt="News Image">
          <div class="card-body">
            <h5 class="card-title">Microbial Warfare in the Gut: Probiotics vs. Dysbiosis</h5>
            <p class="card-text">Probiotics are beneficial bacteria that promote gut health, combating dysbiosis—an imbalance in the gut microbiota linked to various digestive disorders and immune dysfunctions. This microbial warfare within the gut ecosystem highlights the importance of maintaining a healthy balance of gut flora for overall well-being.</p>
            <a href="#" class="btn btn-primary btn-sm">Continue Reading</a>
          </div>
        </div>
      </div>
      <div class="col-md-3 mb-2">
        <div class="card">
          <img src="eve2.png" class="card-img-top" alt="News Image">
          <div class="card-body">
            <h5 class="card-title">Gene Editing Battles Genetic Disorders: CRISPR vs. Inherited Diseases</h5>
            <p class="card-text">Gene editing technologies like CRISPR offer the potential to correct genetic mutations responsible for inherited diseases. This interior medical war involves precise manipulation of DNA sequences to combat conditions ranging from cystic fibrosis to sickle cell anemia, ushering in a new era of personalized medicine.</p>
            <a href="#" class="btn btn-primary btn-sm">Continue Reading</a>
          </div>
        </div>
      </div>
    </div>
   
    
    </section>
  <footer class="text-center py-3 bg-light">
    <p>&copy; 2024 HURAMA Pharma HARISHA S(212223040063)</p>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p" crossorigin="anonymous"></script>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Events</title>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" crossorigin="anonymous">
</head>
<body>

  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">HURAMA Pharma</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item">
            <a class="nav-link" href="app.html">Home</a>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle active" href="#" id="aboutUsDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
              About Us
            </a>
            <ul class="dropdown-menu" aria-labelledby="aboutUsDropdown">
              <li><a class="dropdown-item" href="#">FOUNDATION</a></li>
              <li><a class="dropdown-item" href="#">AIM</a></li>
              <li><a class="dropdown-item" href="#">LEADERS</a></li>
            </ul>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="products.html">Products</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="event.html">Events</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="about.html">Contact</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>


  <section class="container py-5">
    <h1 class="text-center mb-4">News & Events</h1>
    <div class="row">
      <div class="col-md-3 mb-2">
        <div class="card">
          <img src="eve1.png" class="card-img-top" alt="News Image">
          <div class="card-body">
            <h5 class="card-title">Microbial Warfare in the Gut: Probiotics vs. Dysbiosis</h5>
            <p class="card-text">Probiotics are beneficial bacteria that promote gut health, combating dysbiosis—an imbalance in the gut microbiota linked to various digestive disorders and immune dysfunctions. This microbial warfare within the gut ecosystem highlights the importance of maintaining a healthy balance of gut flora for overall well-being.</p>
            <a href="#" class="btn btn-primary btn-sm">Continue Reading</a>
          </div>
        </div>
      </div>
      <div class="col-md-3 mb-2">
        <div class="card">
          <img src="eve2.png" class="card-img-top" alt="News Image">
          <div class="card-body">
            <h5 class="card-title">Gene Editing Battles Genetic Disorders: CRISPR vs. Inherited Diseases</h5>
            <p class="card-text">Gene editing technologies like CRISPR offer the potential to correct genetic mutations responsible for inherited diseases. This interior medical war involves precise manipulation of DNA sequences to combat conditions ranging from cystic fibrosis to sickle cell anemia, ushering in a new era of personalized medicine.</p>
            <a href="#" class="btn btn-primary btn-sm">Continue Reading</a>
          </div>
        </div>
      </div>
    </div>
   
    
    </section>
  <footer class="text-center py-3 bg-light">
    <p>&copy; 2024 HURAMA Pharma HARISHA S(212223040063)</p>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p" crossorigin="anonymous"></script>
</body>
</html>



```


## OUTPUT:

https://github.com/HARISHA2006/Pharma/blob/main/Screenshot%202024-05-09%20042501.png

https://github.com/HARISHA2006/Pharma/blob/main/Screenshot%202024-05-09%20043943.png

https://github.com/HARISHA2006/Pharma/blob/main/Screenshot%202024-05-09%20043951.png

https://github.com/HARISHA2006/Pharma/blob/main/Screenshot%202024-05-09%20044004.png

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
