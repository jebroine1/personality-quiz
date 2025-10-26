# personality-quiz
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Which Track Event Are You?</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
  <link rel="stylesheet" href="style.css">
</head>
<body class="container py-4">

  <h1 class="text-center mb-4">Which Track Event Are You?</h1>

  <!-- Question 1 -->
  <div class="question-block mb-3">
    <h3>1. How would you describe your personality?</h3>
    <button class="btn btn-outline-primary answer-btn" data-score="3">Fast and energetic</button>
    <button class="btn btn-outline-primary answer-btn" data-score="1">Calm and patient</button>
  </div>

  <!-- Question 2 -->
  <div class="question-block mb-3">
    <h3>2. What's your favorite type of workout?</h3>
    <button class="btn btn-outline-primary answer-btn" data-score="3">Sprints or HIIT</button>
    <button class="btn btn-outline-primary answer-btn" data-score="1">Long runs</button>
  </div>

  <!-- Question 3 -->
  <div class="question-block mb-3">
    <h3>3. How do you handle challenges?</h3>
    <button class="btn btn-outline-primary answer-btn" data-score="1">Stay steady and keep going</button>
    <button class="btn btn-outline-primary answer-btn" data-score="3">Attack it head-on</button>
  </div>

  <!-- Button to show results -->
  <button id="results-btn" class="btn btn-success d-block mx-auto mt-4">Show My Result</button>

  <!-- Where the result will appear -->
  <div id="result-container" class="text-center mt-4 fs-4"></div>

  <script src="script.js"></script>
</body>
</html>
