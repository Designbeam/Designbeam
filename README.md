body {
  font-family: 'Segoe UI', sans-serif;
  margin: 0;
  padding: 0;
  background-color: #1e1f1f;
  color: #e0f2f1;
}

header {
  text-align: center;
  padding: 2.5rem 1rem;
  background: linear-gradient(135deg, #263238 0%, #37474f 100%);
  border-bottom: 4px solid #4db6ac;
}

header img {
  max-height: 100px;
  margin-bottom: 1rem;
}

header h1 {
  font-size: 2.5rem;
  color: #4db6ac;
}

header p {
  color: #cfd8dc;
  max-width: 700px;
  margin: auto;
}

#menu-toggle {
  display: none;
  background-color: #4db6ac;
  color: white;
  padding: 0.5rem 1rem;
  border: none;
  font-size: 1rem;
  cursor: pointer;
  margin-top: 1rem;
}

#main-nav {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 1rem;
  margin-top: 1rem;
}

#main-nav a {
  color: #e0f2f1;
  text-decoration: none;
  font-weight: bold;
}

#main-nav a:hover {
  background-color: #4db6ac;
  color: #000;
  padding: 0.5rem;
  border-radius: 5px;
}

@media (max-width: 768px) {
  #menu-toggle {
    display: inline-block;
  }

  #main-nav {
    display: none;
    flex-direction: column;
    align-items: center;
  }

  #main-nav.active {
    display: flex;
  }

  #main-nav a {
    width: 100%;
    text-align: center;
    padding: 0.8rem;
    border-bottom: 1px solid #4db6ac;
  }
}