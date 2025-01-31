
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Interactive Asia Map</title>
  <style>
    svg {
      width: 100%;
      height: auto;
    }
    path {
      fill: #e6e6e6;
      stroke: #999;
      stroke-width: 0.5;
      cursor: pointer;
    }
    path:hover {
      fill: #ffcc00;
    }
  </style>
</head>
<body>
  <h1>Explore Asia</h1>
  <h3>Click on a country to learn more about it:</h3>
  
  <svg viewBox="0 0 1000 700" xmlns="http://www.w3.org/2000/svg">
    <a href="china.md">
      <path id="china" d="M500,200 L520,220 L500,240 Z" alt="China" />
    </a>
    <a href="india.md">
      <path id="india" d="M520,220 L550,240 L520,260 Z" alt="India" />
    </a>
    <a href="japan.md">
      <path id="japan" d="M800,150 L820,170 L800,190 Z" alt="Japan" />
    </a>
    <!-- Add more countries as needed, using similar <a> and <path> elements -->
  </svg>

</body>
</html>
