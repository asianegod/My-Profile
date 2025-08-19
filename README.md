/* Skip link ẩn đi, chỉ hiện khi focus */
.skip-link {
  position: absolute;
  left: -999px;
  top: auto;
}
.skip-link:focus {
  left: 10px;
  top: 10px;
  background: yellow;
  padding: 5px;
  border: 1px solid black;
}

/* Navigation với flex */
.nav {
  display: flex;
  gap: 20px;
  list-style: none;
  background: #333;
  padding: 10px;
}
.nav a {
  color: white;
  text-decoration: none;
}
.nav a:hover {
  color: orange;
  transition: 0.3s;
}

/* Ảnh với box model */
img {
  border: 3px solid #ccc;
  padding: 5px;
  border-radius: 10px;
  max-width: 100%;
}

/* Grid layout cho gallery */
.gallery {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 15px;
}

/* Hover effect */
.gallery img:hover {
  transform: scale(1.05);
  box-shadow: 0 0 10px rgba(0,0,0,0.5);
}

/* nth-child ví dụ */
.gallery img:nth-child(odd) {
  border-radius: 50%;
}
