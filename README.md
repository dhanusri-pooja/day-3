# Day - 3
Today I learned how to make a simple content card using HTML and CSS.
I gave the card a box shadow and rounded corners to make it look soft and clean.

Then, I added a hover effect so when I move the mouse over the card, it:

- Grows slightly
  
- And the shadow becomes deeper

# How I Used CSS:

- CSS is written inside a <style> tag (not external).
- So the HTML and CSS are in the same file.

# Code Used:
  
```
  <!DOCTYPE html>
<html>
<head>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #fff0f5;
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
      padding: 40px;
    }

    .card {
      width: 220px;
      padding: 20px;
      border-radius: 15px;
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.15);
      transition: 0.3s ease;
      color: #333;
      text-align: center;
    }

    .card:hover {
      transform: scale(1.05);
      box-shadow: 0 12px 24px rgba(0, 0, 0, 0.25);
    }

    .card1 { background: linear-gradient(135deg, #ffc2e2, #ffb3ba); }
    .card2 { background: linear-gradient(135deg, #d4fc79, #96e6a1); }
    .card3 { background: linear-gradient(135deg, #e0c3fc, #8ec5fc); }
    .card4 { background: linear-gradient(135deg, #e0bbff, #d7a8f9); }
    .card5 { background: linear-gradient(135deg, #fff1eb, #ace0f9); }
  </style>
</head>
<body>

  <div class="card card1">
    <h3>Card 1</h3>
    <p>Pink & Coral</p>
  </div>

  <div class="card card2">
    <h3>Card 2</h3>
    <p>Fresh Mint</p>
  </div>

  <div class="card card3">
    <h3>Card 3</h3>
    <p>Sky Blue</p>
  </div>

  <div class="card card4">
    <h3>Card 4</h3>
    <p>Lavender Purple</p>
  </div>

  <div class="card card5">
    <h3>Card 5</h3>
    <p>Peach Yellow</p>
  </div>

</body>
</html>

```
