# Project Responsive Web Design using Bootstrap
## Date:15.10.2025

## AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.


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
<!DOCTYPE html>
<html>
<head>
  <title>Dribble</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body class="bg-dark text-light">

  <nav class="navbar navbar-dark bg-black px-4 d-flex justify-content-between align-items-center">
    <span class="navbar-brand mb-0 h1 text-success fw-bold fst-italic">Dribble</span>
    <div>
      <a href="#" class="text-white text-decoration-none fw-bold me-3">Sign in</a>
      <a href="#" class="btn btn-success btn-sm fw-bold">Login</a>
    </div>
  </nav>

  <section class="bg-secondary text-center py-4">
    <h4 class="fw-bold">What are you working on?</h4><p>Dribble is show and tell for designers.</p>

    <div class="mt-3">
      <button class="btn btn-danger me-2">Learn more</button>
      <button class="btn btn-success">Login</button>
    </div>
    <hr class="border-light mt-4">
  </section>

  <div class="container py-4">
    <div class="row g-4 text-center">

      <div class="col-6 col-md-2">
        <div class="ratio ratio-1x1 bg-dark rounded overflow-hidden">
          <img src="i1.jpeg" alt="Spiderman" class="w-100 h-100 object-fit-cover">
        </div>
        <div class="fw-bold fst-italic mt-2">Spiderman</div>
      </div>

      <div class="col-6 col-md-2">
        <div class="ratio ratio-1x1 bg-dark rounded overflow-hidden">
          <img src="i2.jpeg" alt="IronMan" class="w-100 h-100 object-fit-cover">
        </div>
        <div class="fw-bold fst-italic mt-2">IronMan</div>
      </div>

      <div class="col-6 col-md-2">
        <div class="ratio ratio-1x1 bg-dark rounded overflow-hidden">
          <img src="i3.jpeg" alt="Captain America" class="w-100 h-100 object-fit-cover">
        </div>
        <div class="fw-bold fst-italic mt-2">Captain America</div>
      </div>

      <div class="col-6 col-md-2">
        <div class="ratio ratio-1x1 bg-dark rounded overflow-hidden">
          <img src="i4.jpeg" alt="Batman" class="w-100 h-100 object-fit-cover">
        </div>
        <div class="fw-bold fst-italic mt-2">Batman</div>
      </div>

      <div class="col-6 col-md-2">
        <div class="ratio ratio-1x1 bg-dark rounded overflow-hidden">
          <img src="i5.jpeg" alt="Deadpool" class="w-100 h-100 object-fit-cover">
        </div>
        <div class="fw-bold fst-italic mt-2">Deadpool</div>
      </div>

      <div class="col-6 col-md-2">
        <div class="ratio ratio-1x1 bg-dark rounded overflow-hidden">
          <img src="i6.jpeg" alt="Venom" class="w-100 h-100 object-fit-cover">
        </div>
        <div class="fw-bold fst-italic mt-2">Venom</div>
      </div>

      <div class="col-6 col-md-2">
        <div class="ratio ratio-1x1 bg-dark rounded overflow-hidden">
          <img src="i7.jpeg" alt="Wolverine" class="w-100 h-100 object-fit-cover">
        </div>
        <div class="fw-bold fst-italic mt-2">Wolverine</div>
      </div>

      <div class="col-6 col-md-2">
        <div class="ratio ratio-1x1 bg-dark rounded overflow-hidden">
          <img src="i8.jpeg" alt="Car" class="w-100 h-100 object-fit-cover">
        </div>
        <div class="fw-bold fst-italic mt-2">Car</div>
      </div>

      <div class="col-6 col-md-2">
        <div class="ratio ratio-1x1 bg-dark rounded overflow-hidden">
          <img src="i9.jpeg" alt="One Piece" class="w-100 h-100 object-fit-cover">
        </div>
        <div class="fw-bold fst-italic mt-2">One Piece</div>
      </div>

      <div class="col-6 col-md-2">
        <div class="ratio ratio-1x1 bg-dark rounded overflow-hidden">
          <img src="i10.jpeg" alt="Luffy" class="w-100 h-100 object-fit-cover">
        </div>
        <div class="fw-bold fst-italic mt-2">Luffy</div>
      </div>

      <div class="col-6 col-md-2">
        <div class="ratio ratio-1x1 bg-dark rounded overflow-hidden">
          <img src="i11.jpeg" alt="Zoro" class="w-100 h-100 object-fit-cover">
        </div>
        <div class="fw-bold fst-italic mt-2">Zoro</div>
      </div>

      <div class="col-6 col-md-2">
        <div class="ratio ratio-1x1 bg-dark rounded overflow-hidden">
          <img src="i12.jpeg" alt="Kratos" class="w-100 h-100 object-fit-cover">
        </div>
        <div class="fw-bold fst-italic mt-2">Kratos</div>
      </div>

      <div class="col-6 col-md-2">
        <div class="ratio ratio-1x1 bg-dark rounded overflow-hidden">
          <img src="i13.jpeg" alt="Miles Morales" class="w-100 h-100 object-fit-cover">
        </div>
        <div class="fw-bold fst-italic mt-2">Miles Morales</div>
      </div>

      <div class="col-6 col-md-2">
        <div class="ratio ratio-1x1 bg-dark rounded overflow-hidden">
          <img src="i14.jpeg" alt="Infinity Gauntlet" class="w-100 h-100 object-fit-cover">
        </div>
        <div class="fw-bold fst-italic mt-2">Infinity Gauntlet</div>
      </div>

      <div class="col-6 col-md-2">
        <div class="ratio ratio-1x1 bg-dark rounded overflow-hidden">
          <img src="i15.jpeg" alt="Thanos" class="w-100 h-100 object-fit-cover">
        </div>
        <div class="fw-bold fst-italic mt-2">Thanos</div>
      </div>

      <div class="col-6 col-md-2">
        <div class="ratio ratio-1x1 bg-dark rounded overflow-hidden">
          <img src="i16.jpeg" alt="Hulk" class="w-100 h-100 object-fit-cover">
        </div>
        <div class="fw-bold fst-italic mt-2">Hulk</div>
      </div>

      <div class="col-6 col-md-2">
        <div class="ratio ratio-1x1 bg-dark rounded overflow-hidden">
          <img src="i17.jpeg" alt="IronMan" class="w-100 h-100 object-fit-cover">
        </div>
        <div class="fw-bold fst-italic mt-2">IronMan</div>
      </div>

      <div class="col-6 col-md-2">
        <div class="ratio ratio-1x1 bg-dark rounded overflow-hidden">
          <img src="i18.jpeg" alt="Itachi" class="w-100 h-100 object-fit-cover">
        </div>
        <div class="fw-bold fst-italic mt-2">Itachi</div>
      </div>

    </div>
  </div>

</body>
</html>
```


## OUTPUT:
![alt text](<Screenshot (45).png>)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
