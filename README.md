# Seng-assignmentttt-signmenttttgg
dele was here
/* Reset default margin and padding */
body, ul {
  margin: 0;
  padding: 0;
}

/* Navigation Bar */
nav ul {
  list-style-type: none;
  background-color: #f5f5f5;
  padding: 10px;
}

nav ul li {
  display: inline;
  margin-right: 10px;
}

nav ul li a {
  text-decoration: none;
  color: #333;
  padding: 5px;
}

/* Banner Picture */
img {
  width: 100%;
  max-height: 400px;
}

/* Group Members Section */
section h2 {
  text-align: center;
  margin: 20px 0;
}

section ul {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  list-style-type: none;
  margin: 0;
  padding: 0;
}

section li {
  text-align: center;
  margin: 20px;
}

section a {
  text-decoration: none;
  color: #333;
}

/* Other Pictures Grid Section */
section:nth-child(3) {
  background-color: #f5f5f5;
  padding: 20px;
}

/* Footer */
footer {
  background-color: #f5f5f5;
  padding: 10px;
  text-align: center;
}

footer ul {
  list-style-type: none;
}

/* Media Queries for Responsive Design */
@media (max-width: 768px) {
  img {
    max-height: 300px;
  }
  
  section ul {
    justify-content: flex-start;
  }
  
  section li {
    margin: 10px;
  }
}
